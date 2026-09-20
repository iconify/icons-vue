<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kdyx2sb9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kdyx2sb9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:volleyball2" /></template>
