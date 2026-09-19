<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft94xac-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":496};
const content = `<path class="ft94xac-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:shopping-cart" /></template>
