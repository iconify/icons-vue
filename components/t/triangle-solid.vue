<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pf3o_obyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pf3o_obyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:triangle-solid" /></template>
