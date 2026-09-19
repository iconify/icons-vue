<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gpdwt3flt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gpdwt3flt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:ticket" /></template>
