<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_p7_xt8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="w_p7_xt8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:signal-full" /></template>
