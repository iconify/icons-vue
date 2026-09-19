<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tcueq7bxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="tcueq7bxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:select-all" /></template>
