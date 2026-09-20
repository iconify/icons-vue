<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qq4h2u3rg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qq4h2u3rg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:processon" /></template>
