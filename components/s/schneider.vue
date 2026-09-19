<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d4tlsrb4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d4tlsrb4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:schneider" /></template>
