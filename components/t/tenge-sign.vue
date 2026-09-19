<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7rp-2o6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="l7rp-2o6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:tenge-sign" /></template>
