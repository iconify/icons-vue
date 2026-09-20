<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dk_rxnbss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="dk_rxnbss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:virus" /></template>
