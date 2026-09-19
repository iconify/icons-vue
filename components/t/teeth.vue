<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/c/c8p3g3byb.css';
import '../../css/a/acjzmsjdx.css';
import '../../css/p/pvmqixbkk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><path clip-rule="evenodd" class="c8p3g3byb"/><path class="acjzmsjdx"/><path class="pvmqixbkk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:teeth" /></template>
