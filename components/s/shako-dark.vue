<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxufv2zqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qxufv2zqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:shako-dark" /></template>
