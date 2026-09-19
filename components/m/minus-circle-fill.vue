<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2y2oabkw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r2y2oabkw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:minus-circle-fill" /></template>
