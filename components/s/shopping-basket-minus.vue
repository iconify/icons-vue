<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uu49r2jkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uu49r2jkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:shopping-basket-minus" /></template>
