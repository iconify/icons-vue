<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xe3f5lbat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xe3f5lbat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:reel" /></template>
