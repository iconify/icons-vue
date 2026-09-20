<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yjew7nbsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yjew7nbsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:pen-off-sharp" /></template>
