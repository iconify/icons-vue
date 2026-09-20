<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vxji0o-1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vxji0o-1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:nuxt" /></template>
