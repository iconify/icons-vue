<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nv55mnb9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="nv55mnb9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:recurringappointment" /></template>
