<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gt3yji6_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gt3yji6_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:toolscopy" /></template>
