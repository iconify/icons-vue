<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t4fb2tf6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="t4fb2tf6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:markup-stroke-12" /></template>
