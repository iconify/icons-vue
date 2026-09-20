<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/b/blvqrmbuc.css';
import '../../css/s/s_u7kz7uj.css';
import '../../css/r/ruhx5ib9r.css';
import '../../css/l/la5s4p9kx.css';
import '../../css/o/o9l509dbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="blvqrmbuc"/><path class="s_u7kz7uj"/><path class="ruhx5ib9r"/><path class="la5s4p9kx"/><path class="o9l509dbn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:office-shredder-1" /></template>
