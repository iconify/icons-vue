<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2kyjzsvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="r2kyjzsvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:triangle-arrow-transfer-diagonal-3-remix" /></template>
