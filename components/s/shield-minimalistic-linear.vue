<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djh_z1beg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="djh_z1beg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:shield-minimalistic-linear" /></template>
