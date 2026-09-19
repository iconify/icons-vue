<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oei9pubwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oei9pubwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:sign-plus-square-bold" /></template>
