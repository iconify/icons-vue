<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/igezxozon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="igezxozon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:preregistered-de-plus-square" /></template>
