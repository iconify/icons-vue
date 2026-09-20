<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kupompbrn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kupompbrn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:sendgrid" /></template>
