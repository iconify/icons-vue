<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lgeb-gxyl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lgeb-gxyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:shopping-cart-remove-01" /></template>
