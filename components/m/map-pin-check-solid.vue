<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fh0755-mp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fh0755-mp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:map-pin-check-solid" /></template>
