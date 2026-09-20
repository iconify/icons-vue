<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uoa_vzbef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="uoa_vzbef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:shopping-catergories-chair-design-lounge-furniture-chair-interior-decorate-armchair-decoration" /></template>
