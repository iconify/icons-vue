<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rqunbxb7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rqunbxb7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:shopping-cart-16-solid" /></template>
