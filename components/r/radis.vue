<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/isp8llwmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="isp8llwmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:radis" /></template>
