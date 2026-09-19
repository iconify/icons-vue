<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bpwynwb9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bpwynwb9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:minimize" /></template>
