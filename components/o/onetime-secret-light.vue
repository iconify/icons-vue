<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1xbai7pj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w1xbai7pj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:onetime-secret-light" /></template>
