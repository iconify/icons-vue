<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-1nsqbrh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q-1nsqbrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:star-fill" /></template>
