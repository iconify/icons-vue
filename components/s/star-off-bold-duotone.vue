<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iwfo2luxv.css';
import '../../css/z/z1_6pqjiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iwfo2luxv"/><path class="z1_6pqjiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:star-off-bold-duotone" /></template>
