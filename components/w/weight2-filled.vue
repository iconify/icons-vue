<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6trnpb7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i6trnpb7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:weight2-filled" /></template>
