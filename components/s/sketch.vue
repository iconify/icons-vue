<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gafqlvo9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gafqlvo9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:sketch" /></template>
