<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/j/jaokbwnxj.css';
import '../../css/l/lab3a5b9w.css';
import '../../css/m/mezep8bdy.css';
import '../../css/b/bos983bva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="jaokbwnxj"/><path class="lab3a5b9w wm-a"/><path class="mezep8bdy wm-a"/><path class="bos983bva"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:thumbs-down-duo" /></template>
