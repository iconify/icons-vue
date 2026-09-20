<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-ilo-gvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="v-ilo-gvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:plugin" /></template>
