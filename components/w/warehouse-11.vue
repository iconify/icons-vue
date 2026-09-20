<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mhyjuybmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="mhyjuybmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:warehouse-11" /></template>
