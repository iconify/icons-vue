<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/ww7cfhb8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ww7cfhb8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:portrait-framed" /></template>
