<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wo2nz1lwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wo2nz1lwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:send2" /></template>
