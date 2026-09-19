<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kx9a0_b4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kx9a0_b4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:shopping-basket-plus-filled" /></template>
