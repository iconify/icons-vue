<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vpbaom0_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vpbaom0_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:table-add" /></template>
