<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qqw0eob9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qqw0eob9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-volume-low" /></template>
