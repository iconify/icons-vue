<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/liy7sib8p.css';
import '../../css/o/onabgabdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="liy7sib8p"/><path class="onabgabdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:videocam-off-outline" /></template>
