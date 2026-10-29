<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/p/prwmzh75z.css';
import '../../css/a/ayhs6pbko.css';
import '../../css/l/l7ckfcc9c.css';
import '../../css/i/iqyqpg9id.css';
import '../../css/s/s53tgbb5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="prwmzh75z wm-deco"/><path class="ayhs6pbko wm-deco"/><path class="l7ckfcc9c wm-k"/><path class="iqyqpg9id wm-k"/><path class="s53tgbb5w wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:split-blueprint" /></template>
