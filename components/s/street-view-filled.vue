<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iu5xwibvu.css';
import '../../css/n/nswg25bfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iu5xwibvu"/><path class="nswg25bfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:street-view-filled" /></template>
