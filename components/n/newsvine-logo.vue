<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kuiqhgduf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kuiqhgduf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:newsvine-logo" /></template>
