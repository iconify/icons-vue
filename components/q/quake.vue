<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yboa2tbap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":896,"height":1024};
const content = `<path class="yboa2tbap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:quake" /></template>
