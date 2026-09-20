<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f88f6cb-x.css';
import '../../css/a/a2th6qhaq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f88f6cb-x"/><path class="a2th6qhaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:piped-light" /></template>
