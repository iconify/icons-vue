<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cty9l0r9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cty9l0r9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:mysa-thermostat" /></template>
