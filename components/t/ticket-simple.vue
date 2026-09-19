<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jip_zkn3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="jip_zkn3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:ticket-simple" /></template>
