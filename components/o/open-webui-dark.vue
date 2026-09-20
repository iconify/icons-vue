<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d8exjwjis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d8exjwjis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:open-webui-dark" /></template>
