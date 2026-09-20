<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aqih82bde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aqih82bde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:terminal-alt-line" /></template>
