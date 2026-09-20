<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m4sk38i8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m4sk38i8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:search-2-plus-sharp" /></template>
