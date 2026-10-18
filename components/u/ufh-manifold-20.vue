<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9n5x7btr.css';
import '../../css/e/e9it5tbme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="k9n5x7btr"/><path class="e9it5tbme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ufh-manifold-20" /></template>
