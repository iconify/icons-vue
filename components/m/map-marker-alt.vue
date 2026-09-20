<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4x1bs.css';
import '../../css/n/ntj7kf.css';
import '../../css/d/d-jkxijw.css';
import '../../css/r/r-to-0px.css';
import '../../css/r/r-to-2_5px.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s4x1bs"/><circle class="ntj7kf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:map-marker-alt" /></template>
