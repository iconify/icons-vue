<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fwrzs0fwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fwrzs0fwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:soundcloud" /></template>
