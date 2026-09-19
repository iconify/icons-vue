<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e2s4x9i3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e2s4x9i3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:twinly-c9" /></template>
