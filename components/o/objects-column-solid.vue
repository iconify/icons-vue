<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q0dhl_bpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q0dhl_bpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:objects-column-solid" /></template>
