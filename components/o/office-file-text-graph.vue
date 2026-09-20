<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/y/yt-yz9bad.css';
import '../../css/i/it19jcb5q.css';
import '../../css/s/skod2vbuj.css';
import '../../css/e/e-_y97b5b.css';
import '../../css/o/o0s61pf4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="yt-yz9bad"/><path class="it19jcb5q"/><path class="skod2vbuj"/><path class="e-_y97b5b"/><path class="o0s61pf4c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:office-file-text-graph" /></template>
