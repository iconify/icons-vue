<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_ge1pb_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k_ge1pb_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:street-sign-line" /></template>
