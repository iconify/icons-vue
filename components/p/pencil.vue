<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sttrdl2yq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sttrdl2yq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:pencil" /></template>
