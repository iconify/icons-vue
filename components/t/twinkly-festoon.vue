<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ugtxpdbiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ugtxpdbiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:twinkly-festoon" /></template>
