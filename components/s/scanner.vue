<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/k/k2ie8jb8l.css';
import '../../css/s/svvboyblr.css';
import '../../css/q/qhkw6xb9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="k2ie8jb8l"/><path class="svvboyblr"/><path class="qhkw6xb9i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:scanner" /></template>
