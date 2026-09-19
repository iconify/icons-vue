<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ci5w0x1se.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ci5w0x1se"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:overseerr" /></template>
