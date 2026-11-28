<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-f6l0bmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k-f6l0bmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:seed" /></template>
