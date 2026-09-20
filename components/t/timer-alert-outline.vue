<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5u5voitv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v5u5voitv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:timer-alert-outline" /></template>
