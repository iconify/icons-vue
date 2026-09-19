<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dhn3e7ber.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dhn3e7ber"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:notification-cancel-filled" /></template>
