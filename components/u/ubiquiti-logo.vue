<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nq4discyn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nq4discyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ubiquiti-logo" /></template>
