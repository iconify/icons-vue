<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ahave22wm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ahave22wm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:maps-off" /></template>
