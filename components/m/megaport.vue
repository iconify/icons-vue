<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wj3z_faaw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="wj3z_faaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:megaport" /></template>
