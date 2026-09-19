<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ps12n-bxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ps12n-bxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:std-floodlight" /></template>
