<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c4yg0k.css';
import '../../css/n/ntj7kf.css';
import '../../css/d/d-jkxijw.css';
import '../../css/t/tr-7ecuqx.css';
import '../../css/r/r-to-0px.css';
import '../../css/r/r-to-2_5px.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c4yg0k"/><circle class="ntj7kf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:map-marker-alt-loop" /></template>
