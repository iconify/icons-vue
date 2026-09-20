<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fz_y9zzsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fz_y9zzsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:wrench-sharp" /></template>
