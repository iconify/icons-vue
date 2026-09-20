<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uigy95ber.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uigy95ber"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:user-clear-filled" /></template>
