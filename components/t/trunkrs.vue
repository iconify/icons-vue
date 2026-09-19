<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hn64xzbjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hn64xzbjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:trunkrs" /></template>
