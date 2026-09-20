<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bohhjnb0p.css';
import '../../css/h/hstms5foq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="bohhjnb0p"/><path clip-rule="evenodd" class="hstms5foq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:png-solid" /></template>
