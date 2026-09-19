<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i7vuirbjs.css';
import '../../css/p/p3gjzeb-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="i7vuirbjs"/><path class="p3gjzeb-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:new-window-fill-16" /></template>
