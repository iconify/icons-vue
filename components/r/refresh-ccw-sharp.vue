<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qq-yi4adu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qq-yi4adu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:refresh-ccw-sharp" /></template>
