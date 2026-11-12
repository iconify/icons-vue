<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zo32ugb2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zo32ugb2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:scraparr-dark" /></template>
