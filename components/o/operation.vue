<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fl7ogccrr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="fl7ogccrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:operation" /></template>
