<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v6ln_hbvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v6ln_hbvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:sort-numeric-descending-variant" /></template>
