<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ukq-o_bfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ukq-o_bfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:send-sharp-fill" /></template>
