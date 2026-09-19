<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/phof8m8ve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="phof8m8ve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:panel-glass-door-open" /></template>
