<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bvsucgsri.css';
import '../../css/b/bfzo5mbpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bvsucgsri"/><path class="bfzo5mbpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:volume-x-20-bold" /></template>
