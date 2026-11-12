<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jvqnthbsg.css';
import '../../css/b/bh48ipmmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jvqnthbsg"/><path class="bh48ipmmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:raygun-monitoring-light" /></template>
