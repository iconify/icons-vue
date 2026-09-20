<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fs7zclvbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fs7zclvbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:xmark" /></template>
