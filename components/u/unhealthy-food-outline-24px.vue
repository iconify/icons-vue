<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fn1axbbvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fn1axbbvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:unhealthy-food-outline-24px" /></template>
