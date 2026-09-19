<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fwm6ibbhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fwm6ibbhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:sync-module" /></template>
