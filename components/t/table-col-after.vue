<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rq36f3btg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="rq36f3btg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:table-col-after" /></template>
