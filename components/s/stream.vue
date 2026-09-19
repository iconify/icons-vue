<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dbi7ckrjh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dbi7ckrjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:stream" /></template>
