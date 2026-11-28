<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3p4ubeee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v3p4ubeee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:user-clock" /></template>
