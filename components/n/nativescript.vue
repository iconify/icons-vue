<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xfo45p3ee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xfo45p3ee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:nativescript" /></template>
