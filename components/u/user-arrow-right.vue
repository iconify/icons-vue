<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-he_3dyq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k-he_3dyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:user-arrow-right" /></template>
