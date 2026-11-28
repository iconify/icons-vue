<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qypqtym9h.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/b/bs3qkuyvu.css';
import '../../css/p/p0z9gxbvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qypqtym9h secondary"/><g class="dt0cm9dhy primary"><path class="bs3qkuyvu"/><path class="p0z9gxbvk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:wand-duo" /></template>
