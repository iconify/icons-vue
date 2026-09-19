<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pioptztzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pioptztzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:panel-glass-door3-close" /></template>
