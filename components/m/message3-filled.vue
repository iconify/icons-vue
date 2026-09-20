<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oddw4b50v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oddw4b50v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:message3-filled" /></template>
