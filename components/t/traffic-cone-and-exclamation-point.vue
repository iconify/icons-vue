<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xkvxmlbra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="xkvxmlbra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:traffic-cone-and-exclamation-point" /></template>
