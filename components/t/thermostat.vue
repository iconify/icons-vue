<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iq7xt_-ek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iq7xt_-ek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:thermostat" /></template>
