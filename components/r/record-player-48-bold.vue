<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxdnnozti.css';
import '../../css/r/rm8mvg9xh.css';
import '../../css/r/r1mw8e2fu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bxdnnozti"/><path class="rm8mvg9xh"/><path class="r1mw8e2fu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:record-player-48-bold" /></template>
