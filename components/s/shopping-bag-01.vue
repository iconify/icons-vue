<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/htl8_ibad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="htl8_ibad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:shopping-bag-01" /></template>
