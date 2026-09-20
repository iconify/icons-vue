<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/de25tub4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="de25tub4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:posthog" /></template>
