<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vgzn514zn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vgzn514zn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:norish" /></template>
