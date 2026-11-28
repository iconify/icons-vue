<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fqs6jwblf.css';
import '../../css/i/i2jdkabow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fqs6jwblf secondary"/><path class="i2jdkabow primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:vase-duo" /></template>
