<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxejd1xoc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cxejd1xoc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:treasure-chest" /></template>
