<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qa-p8-bgn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qa-p8-bgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:worm" /></template>
