<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ee58kac0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ee58kac0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:map-pin-check" /></template>
