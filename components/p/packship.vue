<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gec-ygbwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gec-ygbwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:packship" /></template>
