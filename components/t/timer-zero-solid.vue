<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kl99exb8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kl99exb8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:timer-zero-solid" /></template>
