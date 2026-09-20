<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wo5ibeb6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wo5ibeb6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:stethoscope" /></template>
