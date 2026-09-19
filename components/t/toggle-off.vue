<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eg6zfdsmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="eg6zfdsmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:toggle-off" /></template>
