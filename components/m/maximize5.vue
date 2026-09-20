<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ld8kjwf-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ld8kjwf-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:maximize5" /></template>
