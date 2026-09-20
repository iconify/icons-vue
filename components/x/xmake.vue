<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t7b0d_b0i.css';
import '../../css/h/h8nlay8ur.css';
import '../../css/l/l7jcqeb3y.css';
import '../../css/q/q4ug01b1h.css';
import '../../css/g/ggghmlb3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<circle class="t7b0d_b0i"/><path class="h8nlay8ur"/><path class="l7jcqeb3y"/><path class="q4ug01b1h"/><path class="ggghmlb3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:xmake" /></template>
