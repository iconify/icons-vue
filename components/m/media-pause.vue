<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gwfckxbrm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gwfckxbrm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:media-pause" /></template>
