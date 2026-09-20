<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bimolobtx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bimolobtx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:microphone-alt-solid" /></template>
