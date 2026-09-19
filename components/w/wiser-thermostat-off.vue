<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ew8qlfbax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ew8qlfbax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:wiser-thermostat-off" /></template>
