<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rheme10ad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="rheme10ad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:sticker-mule" /></template>
