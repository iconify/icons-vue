<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rn3g53b9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="rn3g53b9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:plus-square-o" /></template>
