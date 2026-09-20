<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dw0an_lir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dw0an_lir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:unarchive" /></template>
