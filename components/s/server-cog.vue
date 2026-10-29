<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/c/cgi6aebyp.css';
import '../../css/j/jes-ovvpz.css';
import '../../css/e/ekmlpmtjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="cgi6aebyp"/><path class="jes-ovvpz wm-a"/><path class="ekmlpmtjg wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:server-cog" /></template>
