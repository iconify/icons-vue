<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m7p_c-n3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m7p_c-n3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:skip-forward" /></template>
