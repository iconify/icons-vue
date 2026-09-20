<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9q-2bb0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="l9q-2bb0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:serving" /></template>
