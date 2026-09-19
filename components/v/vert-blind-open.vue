<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dq0rzh6os.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dq0rzh6os"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:vert-blind-open" /></template>
