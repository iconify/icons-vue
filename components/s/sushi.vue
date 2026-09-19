<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nyn6rc_-u.css';
import '../../css/j/j_ie9rx3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nyn6rc_-u"/><ellipse class="j_ie9rx3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:sushi" /></template>
