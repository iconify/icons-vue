<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iti7hsb0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iti7hsb0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:programming-user-chat-bold" /></template>
