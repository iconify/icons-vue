<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cqjltqlri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="cqjltqlri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:peso" /></template>
