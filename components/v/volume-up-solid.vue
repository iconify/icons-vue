<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rf5mnlbnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rf5mnlbnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:volume-up-solid" /></template>
