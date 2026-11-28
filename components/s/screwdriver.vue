<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oxxn8ualk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oxxn8ualk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:screwdriver" /></template>
