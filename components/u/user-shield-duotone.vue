<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/f7it3kbjv.css';
import '../../css/u/u5rk34b7w.css';
import '../../css/b/byfs_db6m.css';
import '../../css/g/g7-z5_thi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="f7it3kbjv"/><path class="u5rk34b7w"/><path class="byfs_db6m"/><path class="g7-z5_thi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:user-shield-duotone" /></template>
