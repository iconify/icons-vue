<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uj4i3hkdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uj4i3hkdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:ubt" /></template>
