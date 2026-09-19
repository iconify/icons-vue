<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_ix7sbmr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f_ix7sbmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:samsung" /></template>
