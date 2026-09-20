<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/er1-rxuno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="er1-rxuno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:message-square-check" /></template>
