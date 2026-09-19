<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/npdp7k8ew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="npdp7k8ew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:remove-circle" /></template>
