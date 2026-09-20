<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fknewjbjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fknewjbjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:vuejs-fill" /></template>
