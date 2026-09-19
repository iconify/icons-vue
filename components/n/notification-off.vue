<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/do8im349k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="do8im349k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mono-icons:notification-off" /></template>
