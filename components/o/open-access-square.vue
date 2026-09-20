<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bu1_c1gnp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="bu1_c1gnp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:open-access-square" /></template>
