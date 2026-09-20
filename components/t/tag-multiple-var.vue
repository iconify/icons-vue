<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/luwgkacuh.css';
import '../../css/d/dtm6gbcnd.css';
import '../../css/f/fgc-j2bug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="luwgkacuh"/><circle transform="rotate(-45 8.562 7.667)" class="dtm6gbcnd"/><path class="fgc-j2bug"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:tag-multiple-var" /></template>
