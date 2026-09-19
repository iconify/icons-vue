<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gc0qugbit.css';
import '../../css/n/nvekhcocz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gc0qugbit"/><path class="nvekhcocz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:sort-amount-desc" /></template>
