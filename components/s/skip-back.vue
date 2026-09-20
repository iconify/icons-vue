<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tri6pru9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tri6pru9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:skip-back" /></template>
