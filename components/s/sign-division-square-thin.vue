<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/to-5kdesz.css';
import '../../css/m/msy8t2bre.css';
import '../../css/c/c50uhqblm.css';
import '../../css/j/j7gjjlbfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="to-5kdesz"><path class="msy8t2bre"/><path class="c50uhqblm"/><path class="j7gjjlbfy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:sign-division-square-thin" /></template>
