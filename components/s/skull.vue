<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qddxtrr9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qddxtrr9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:skull" /></template>
