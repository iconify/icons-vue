<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oxgjq0bfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oxgjq0bfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:paper-airplane" /></template>
