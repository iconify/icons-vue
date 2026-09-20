<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3epa78jl.css';
import '../../css/b/b11srpowt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y3epa78jl"/><path class="b11srpowt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:town-filled" /></template>
