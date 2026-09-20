<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l76j_08rg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="l76j_08rg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:vector" /></template>
