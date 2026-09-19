<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gqmerm4nv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gqmerm4nv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:shield-minus" /></template>
