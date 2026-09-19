<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/f/f69ughbml.css';
import '../../css/i/iass40n0e.css';
import '../../css/h/h79q5vbot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="f69ughbml"/><circle class="iass40n0e"/><path class="h79q5vbot"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:warehousing" /></template>
