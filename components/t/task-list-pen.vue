<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/omg2x9c5d.css';
import '../../css/r/r887q9nnn.css';
import '../../css/i/iuephsr1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="omg2x9c5d"/><path class="r887q9nnn"/><path class="iuephsr1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:task-list-pen" /></template>
