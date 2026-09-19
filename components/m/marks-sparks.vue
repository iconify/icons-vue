<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ldg4urbeg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ldg4urbeg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:marks-sparks" /></template>
