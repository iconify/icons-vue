<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hzudws-br.css';
import '../../css/n/nnhz2fbfy.css';
import '../../css/f/f26-q2vvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hzudws-br wm-shadow"/><path class="nnhz2fbfy wm-k"/><path class="f26-q2vvv wm-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-pastel:rotate-ccw" /></template>
