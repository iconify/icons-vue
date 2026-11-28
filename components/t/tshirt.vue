<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jqdx4ebjk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jqdx4ebjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:tshirt" /></template>
