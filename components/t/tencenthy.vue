<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ava_mjgsq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ava_mjgsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:tencenthy" /></template>
