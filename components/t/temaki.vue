<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ylas96bup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ylas96bup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:temaki" /></template>
