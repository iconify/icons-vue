<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ou7pau45d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ou7pau45d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:swipe-down-filled" /></template>
