<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x3gcr_bxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="x3gcr_bxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:triangle-down-fill" /></template>
