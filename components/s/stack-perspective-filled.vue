<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/olqwrl1db.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="olqwrl1db"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:stack-perspective-filled" /></template>
