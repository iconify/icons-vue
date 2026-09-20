<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dafub4b3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dafub4b3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:warning" /></template>
