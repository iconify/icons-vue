<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w65lbnl5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w65lbnl5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:playlist3" /></template>
