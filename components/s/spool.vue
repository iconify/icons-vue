<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1hby5b5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c1hby5b5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:spool" /></template>
