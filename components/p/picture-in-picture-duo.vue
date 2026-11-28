<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djy0icb9y.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/c/c4tsdsd3z.css';
import '../../css/o/o1ow3qbig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="djy0icb9y secondary"/><g class="dt0cm9dhy primary"><path class="c4tsdsd3z"/><path class="o1ow3qbig"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:picture-in-picture-duo" /></template>
