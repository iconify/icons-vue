<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0jsy2bsu.css';
import '../../css/t/t3y7hc53e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z0jsy2bsu"/><path class="t3y7hc53e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pequeroku" /></template>
