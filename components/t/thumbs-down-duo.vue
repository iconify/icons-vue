<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rw8xrvjbq.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/o/ouxafviye.css';
import '../../css/l/l-21uxusr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rw8xrvjbq secondary"/><g class="dt0cm9dhy primary"><path class="ouxafviye"/><path class="l-21uxusr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:thumbs-down-duo" /></template>
