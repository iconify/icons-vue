<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hg06y9bau.css';
import '../../css/j/j02yjqo5b.css';
import '../../css/v/vxu1d29jo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hg06y9bau"/><path class="j02yjqo5b"/><path class="vxu1d29jo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:substation-20" /></template>
