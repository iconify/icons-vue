<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/em4_z4t5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="em4_z4t5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp-color:wrench-flat" /></template>
