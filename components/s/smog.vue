<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xh3pkp80f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="xh3pkp80f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:smog" /></template>
