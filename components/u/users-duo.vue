<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/s/si0ilm6lo.css';
import '../../css/h/h27ihsf5q.css';
import '../../css/p/pfuoo_vfp.css';
import '../../css/z/zu7t2wbxf.css';
import '../../css/s/sdi9acbkd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="si0ilm6lo"/><path class="h27ihsf5q wm-a"/><path class="pfuoo_vfp"/><path class="wm-a zu7t2wbxf"/><path class="sdi9acbkd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:users-duo" /></template>
