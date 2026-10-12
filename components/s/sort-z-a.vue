<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mmnj32bie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mmnj32bie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:sort-z-a" /></template>
