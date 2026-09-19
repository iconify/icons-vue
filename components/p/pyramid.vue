<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sny75bc3q.css';
import '../../css/h/h0-przbga.css';
import '../../css/d/dwuyinbfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="sny75bc3q"/><path class="h0-przbga"/><path class="dwuyinbfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:pyramid" /></template>
