<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wt4q6qbni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wt4q6qbni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:shaarli-dark" /></template>
