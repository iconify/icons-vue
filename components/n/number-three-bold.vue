<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m0karrb9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m0karrb9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:number-three-bold" /></template>
