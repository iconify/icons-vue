<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pf7b53bzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pf7b53bzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:pyg" /></template>
