<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vz6-h_4-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vz6-h_4-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:wifi-slash" /></template>
