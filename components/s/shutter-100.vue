<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uto-v3b6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uto-v3b6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:shutter-100" /></template>
