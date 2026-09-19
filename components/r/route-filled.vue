<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/guy_c8bab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="guy_c8bab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:route-filled" /></template>
