<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gcjm71btb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gcjm71btb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:sign-plus-thin" /></template>
