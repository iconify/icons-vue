<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjgud8baq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rjgud8baq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:phone-fill" /></template>
