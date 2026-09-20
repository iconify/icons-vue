<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ay9_sac9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="ay9_sac9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:wlan-strength-3-lock" /></template>
