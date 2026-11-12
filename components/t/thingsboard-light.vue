<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zu07umcxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zu07umcxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:thingsboard-light" /></template>
