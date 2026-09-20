<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ihxn32mfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ihxn32mfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:ultron" /></template>
