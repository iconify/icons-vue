<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/asy189blx.css';
import '../../css/l/lveuvsb7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="asy189blx"/><path class="lveuvsb7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:security-user-lock" /></template>
