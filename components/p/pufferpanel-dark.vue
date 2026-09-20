<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gg5j9mb9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gg5j9mb9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pufferpanel-dark" /></template>
