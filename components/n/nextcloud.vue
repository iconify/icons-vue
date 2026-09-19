<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uwd1hrb_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="uwd1hrb_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:nextcloud" /></template>
