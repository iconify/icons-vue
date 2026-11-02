<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/frc6tjsrn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="frc6tjsrn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:twitter-fill" /></template>
