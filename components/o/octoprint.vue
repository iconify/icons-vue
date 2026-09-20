<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hadxb356p.css';
import '../../css/o/o8jdmjbti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hadxb356p"/><path class="o8jdmjbti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:octoprint" /></template>
