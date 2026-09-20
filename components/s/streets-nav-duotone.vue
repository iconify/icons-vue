<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/a_kkd2brg.css';
import '../../css/g/g73wvxbdb.css';
import '../../css/a/a3cqnpbsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="a_kkd2brg"/><path class="g73wvxbdb"/><path class="a3cqnpbsa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:streets-nav-duotone" /></template>
