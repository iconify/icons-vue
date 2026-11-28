<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-b3neb6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k-b3neb6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:virus-alert" /></template>
