<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s33psy3qd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s33psy3qd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:pause3-filled" /></template>
