<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vl4e5zrno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vl4e5zrno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:remove-minus-circle" /></template>
