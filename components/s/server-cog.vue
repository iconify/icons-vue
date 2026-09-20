<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/w/weha31b6b.css';
import '../../css/e/ee2t7xd7i.css';
import '../../css/q/qrtaw5usw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="weha31b6b"/><path class="ee2t7xd7i"/><path class="qrtaw5usw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:server-cog" /></template>
