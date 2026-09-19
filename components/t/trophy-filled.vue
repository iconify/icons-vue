<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e6165wbov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e6165wbov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:trophy-filled" /></template>
