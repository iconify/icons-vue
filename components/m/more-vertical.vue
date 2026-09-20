<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vj9wcwbzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="vj9wcwbzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="marketeq:more-vertical" /></template>
