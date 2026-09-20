<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/g0zcltbvt.css';
import '../../css/y/yzfgrg9gk.css';
import '../../css/w/w4e85xboi.css';
import '../../css/n/n3upvwb4q.css';
import '../../css/c/c8eo9-b5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="g0zcltbvt"/><path clip-rule="evenodd" class="yzfgrg9gk"/><path clip-rule="evenodd" class="w4e85xboi"/><path clip-rule="evenodd" class="n3upvwb4q"/><path class="c8eo9-b5b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:playlist-minimalistic-2-bold" /></template>
