<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ghx_27s5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ghx_27s5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:unspash-logo-block" /></template>
