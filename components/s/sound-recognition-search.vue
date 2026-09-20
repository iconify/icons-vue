<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fdxeyrj_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="fdxeyrj_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:sound-recognition-search" /></template>
