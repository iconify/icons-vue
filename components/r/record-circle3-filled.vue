<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v61j59dol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v61j59dol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:record-circle3-filled" /></template>
