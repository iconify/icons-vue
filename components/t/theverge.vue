<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rkwyvac_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":896};
const content = `<path class="rkwyvac_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:theverge" /></template>
