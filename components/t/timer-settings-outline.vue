<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/quiri2l_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="quiri2l_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:timer-settings-outline" /></template>
