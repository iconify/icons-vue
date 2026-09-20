<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/welchcbsj.css';
import '../../css/m/m8tmz5tfa.css';
import '../../css/u/ul_wuibqj.css';
import '../../css/b/bxuuanbpe.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/l/lvvsw5byp.css';
import '../../css/m/mq6ru761b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="welchcbsj"/><path class="m8tmz5tfa"/><path class="ul_wuibqj"/><path class="bxuuanbpe"/><g class="ij2x_72vy"><path class="lvvsw5byp"/><path class="mq6ru761b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:scissors" /></template>
