<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ny7qrabjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="ny7qrabjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="marketeq:microphone" /></template>
