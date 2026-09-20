<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wqzu09b6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wqzu09b6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:simplelogin-dark" /></template>
