<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yr0txkbib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yr0txkbib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:weixin" /></template>
