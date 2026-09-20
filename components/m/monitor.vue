<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_5v_b9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nz_5v_b9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:monitor" /></template>
