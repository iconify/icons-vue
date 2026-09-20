<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czxc6oy_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="czxc6oy_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:user-times-solid" /></template>
