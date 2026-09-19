<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/to-5kdesz.css';
import '../../css/z/zxjbngbxy.css';
import '../../css/g/g8m3171mh.css';
import '../../css/l/l9ewbkbml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="to-5kdesz"><circle class="zxjbngbxy"/><path class="g8m3171mh"/><path class="l9ewbkbml"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:sign-division-circle-light" /></template>
