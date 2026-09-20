<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/razlacc1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="razlacc1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:wlan-strength-1-lock" /></template>
