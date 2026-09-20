<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gwga7p4ik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gwga7p4ik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:stethoscope-bold" /></template>
