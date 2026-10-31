<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/blz8tvbof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="blz8tvbof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:table-minus-corner-fill-round" /></template>
