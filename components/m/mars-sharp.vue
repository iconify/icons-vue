<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qrzks8m2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qrzks8m2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:mars-sharp" /></template>
