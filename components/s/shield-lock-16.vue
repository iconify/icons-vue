<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zrw6ywbyh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zrw6ywbyh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:shield-lock-16" /></template>
