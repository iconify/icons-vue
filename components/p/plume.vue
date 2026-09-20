<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pgyhxkbem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pgyhxkbem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:plume" /></template>
