<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vrb6phh1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vrb6phh1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:pinpoint" /></template>
