<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjcs95bpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sjcs95bpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:tooth-bridge-filled" /></template>
