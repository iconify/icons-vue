<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n923nubfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n923nubfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:trash-can" /></template>
