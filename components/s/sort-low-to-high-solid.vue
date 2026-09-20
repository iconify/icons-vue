<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r1s84rbss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="r1s84rbss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:sort-low-to-high-solid" /></template>
