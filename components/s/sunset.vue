<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/a/a3nlqvb5z.css';
import '../../css/f/ffnf2ab0y.css';
import '../../css/j/jdnh2xb9s.css';
import '../../css/t/twt2d5ihs.css';
import '../../css/h/h9pmkbc5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="a3nlqvb5z"/><path class="ffnf2ab0y"/><path class="jdnh2xb9s"/><path class="twt2d5ihs"/><path class="h9pmkbc5m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:sunset" /></template>
