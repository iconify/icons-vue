<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g3c8hybgh.css';
import '../../css/i/izfww2b3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="g3c8hybgh"/><path class="izfww2b3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-camera" /></template>
