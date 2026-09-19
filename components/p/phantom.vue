<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-y6q5_eh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-y6q5_eh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:phantom" /></template>
