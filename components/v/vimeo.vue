<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dqfn-ipyo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1158.764,"height":1000};
const content = `<path class="dqfn-ipyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="brandico:vimeo" /></template>
