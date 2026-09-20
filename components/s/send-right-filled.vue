<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t8wgp4bha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t8wgp4bha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:send-right-filled" /></template>
