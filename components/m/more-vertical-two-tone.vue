<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hrgyses5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hrgyses5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:more-vertical-two-tone" /></template>
