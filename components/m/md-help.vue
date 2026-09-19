<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qv4n9hbhl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qv4n9hbhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-help" /></template>
