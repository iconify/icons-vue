<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lvwfkvduf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lvwfkvduf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:wellner" /></template>
