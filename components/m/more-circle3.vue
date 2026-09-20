<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ab2by8v5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ab2by8v5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:more-circle3" /></template>
