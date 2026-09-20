<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g8qxi56ew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g8qxi56ew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:notes2" /></template>
