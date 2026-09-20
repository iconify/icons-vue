<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pxx5zlbxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pxx5zlbxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:rainbow" /></template>
