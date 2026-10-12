<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e2xs_abqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="e2xs_abqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:shopping-cart-fill-20" /></template>
