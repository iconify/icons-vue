<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fk4aipm_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fk4aipm_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:tubi-alt" /></template>
