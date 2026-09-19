<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fc9gedb9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fc9gedb9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:x-shield-filled" /></template>
