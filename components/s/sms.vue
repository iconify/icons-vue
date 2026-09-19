<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-4wlnb7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1600};
const content = `<path class="z-4wlnb7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:sms" /></template>
