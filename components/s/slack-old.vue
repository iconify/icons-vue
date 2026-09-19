<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/md1t4lm0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="md1t4lm0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:slack-old" /></template>
