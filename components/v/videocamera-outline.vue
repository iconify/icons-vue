<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y06ns3bwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y06ns3bwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:videocamera-outline" /></template>
