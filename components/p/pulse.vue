<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/afxuf779n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="afxuf779n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:pulse" /></template>
