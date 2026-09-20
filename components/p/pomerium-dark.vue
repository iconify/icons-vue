<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zh5nprbqb.css';
import '../../css/r/rcnhk0biq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zh5nprbqb"/><path class="rcnhk0biq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pomerium-dark" /></template>
