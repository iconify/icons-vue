<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mh2ol5bjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="mh2ol5bjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:time-out" /></template>
