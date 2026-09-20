<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s6y_s-uod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s6y_s-uod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:shield-security-filled" /></template>
