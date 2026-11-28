<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rijdllbpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary rijdllbpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:stroke-line-join-bevel-duotone" /></template>
