<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/w/w84oibczi.css';
import '../../css/a/aw4bac3ch.css';
import '../../css/t/tnjkyilll.css';
import '../../css/z/zsuclwbnx.css';
import '../../css/k/kspoj7vnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="w84oibczi"/><path clip-rule="evenodd" class="aw4bac3ch"/><path clip-rule="evenodd" class="tnjkyilll"/><path class="zsuclwbnx"/><path clip-rule="evenodd" class="kspoj7vnd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:stopwatch-circle-off" /></template>
