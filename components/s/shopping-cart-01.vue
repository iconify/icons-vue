<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lt6gvib0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lt6gvib0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:shopping-cart-01" /></template>
