<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pd7e0lmvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="pd7e0lmvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:share" /></template>
