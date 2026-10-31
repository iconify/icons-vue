<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tq2xwlmto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tq2xwlmto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:microphone-slash-solid" /></template>
