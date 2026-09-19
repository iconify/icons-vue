<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mkyr8tb0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mkyr8tb0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:microphone" /></template>
