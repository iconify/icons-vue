<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-vf2vbak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="c-vf2vbak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:recycle-solid" /></template>
