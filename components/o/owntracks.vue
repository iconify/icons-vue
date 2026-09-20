<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h63zrzbmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h63zrzbmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:owntracks" /></template>
