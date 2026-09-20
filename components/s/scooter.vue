<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wlvs94qcj.css';
import '../../css/a/af5wgxf3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wlvs94qcj"/><path class="af5wgxf3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:scooter" /></template>
