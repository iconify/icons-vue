<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eusr_9bsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eusr_9bsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:panels-left-bottom-sharp" /></template>
