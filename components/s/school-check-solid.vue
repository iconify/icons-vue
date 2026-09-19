<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/e/eyeze3yrd.css';
import '../../css/z/ziaphnbba.css';
import '../../css/a/a5wousakn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="eyeze3yrd"/><path class="ziaphnbba"/><path clip-rule="evenodd" class="a5wousakn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:school-check-solid" /></template>
