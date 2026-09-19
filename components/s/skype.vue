<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oqqgrl6yn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oqqgrl6yn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:skype" /></template>
