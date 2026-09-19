<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xly2t3apw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="xly2t3apw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:plain-text" /></template>
