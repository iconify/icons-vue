<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vjaugxbdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vjaugxbdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:twilio" /></template>
