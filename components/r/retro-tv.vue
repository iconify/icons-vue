<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yg-xa_blz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="yg-xa_blz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:retro-tv" /></template>
