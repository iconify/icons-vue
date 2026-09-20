<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v0o6zdbeq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="v0o6zdbeq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:outdent-ltr" /></template>
