<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p1c3kp_ph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p1c3kp_ph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:netto" /></template>
