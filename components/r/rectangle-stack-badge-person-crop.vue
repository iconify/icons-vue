<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uuvttr7oh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="uuvttr7oh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:rectangle-stack-badge-person-crop" /></template>
