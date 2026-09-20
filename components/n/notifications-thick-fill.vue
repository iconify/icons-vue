<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/keux-obrf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="keux-obrf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:notifications-thick-fill" /></template>
