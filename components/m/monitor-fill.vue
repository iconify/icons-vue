<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gqfws_12w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gqfws_12w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:monitor-fill" /></template>
