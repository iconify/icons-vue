<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hx9xdw4tp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hx9xdw4tp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:table-cells-large" /></template>
