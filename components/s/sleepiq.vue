<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jfnu-gb0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jfnu-gb0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:sleepiq" /></template>
