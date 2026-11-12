<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gevjoxb8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gevjoxb8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ubiquiti-ap" /></template>
