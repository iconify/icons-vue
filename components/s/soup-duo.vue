<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/p/plhvrsb6r.css';
import '../../css/g/g0jhk334h.css';
import '../../css/a/aedlnnets.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="plhvrsb6r"/><path class="g0jhk334h wm-a"/><path class="aedlnnets"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:soup-duo" /></template>
