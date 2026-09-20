<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-e7r8qso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k-e7r8qso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:message-circle-x" /></template>
