<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-mp5cb5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j-mp5cb5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:tfx" /></template>
