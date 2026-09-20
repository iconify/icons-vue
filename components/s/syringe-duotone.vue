<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/mc2zb0bvp.css';
import '../../css/s/sva33pbqa.css';
import '../../css/m/mak1mic-b.css';
import '../../css/q/qoill7eto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><g class="mc2zb0bvp"><path class="sva33pbqa"/><path clip-rule="evenodd" class="mak1mic-b"/></g><path class="qoill7eto"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:syringe-duotone" /></template>
