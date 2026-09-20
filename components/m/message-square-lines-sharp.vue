<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_jda-bzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o_jda-bzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:message-square-lines-sharp" /></template>
