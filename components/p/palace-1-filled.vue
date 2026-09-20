<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jfnqrjbwb.css';
import '../../css/f/ft8o1xber.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jfnqrjbwb"/><path class="ft8o1xber"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:palace-1-filled" /></template>
