<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wh28ngeab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wh28ngeab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:sidebar-bottom-filled" /></template>
