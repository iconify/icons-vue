<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kfpt253yi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kfpt253yi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:timer-off" /></template>
