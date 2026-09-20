<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/no4_6ljhh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="no4_6ljhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:map2-filled" /></template>
