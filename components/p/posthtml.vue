<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b2zpr77lu.css';
import '../../css/q/qhpij3bsp.css';
import '../../css/o/ofnfaeuml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="b2zpr77lu"><path class="qhpij3bsp"/><path class="ofnfaeuml"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:posthtml" /></template>
