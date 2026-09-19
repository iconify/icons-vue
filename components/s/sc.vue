<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yl1c57z_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yl1c57z_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:sc" /></template>
