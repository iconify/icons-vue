<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hz18cqbqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hz18cqbqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:send-email-pop-up" /></template>
