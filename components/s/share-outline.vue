<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qaw9v0bqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qaw9v0bqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:share-outline" /></template>
