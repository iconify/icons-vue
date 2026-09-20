<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g8bx3o-vc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g8bx3o-vc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:notification-bell-question-mark-fill" /></template>
