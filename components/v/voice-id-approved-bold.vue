<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ngvbhrcoo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ngvbhrcoo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:voice-id-approved-bold" /></template>
