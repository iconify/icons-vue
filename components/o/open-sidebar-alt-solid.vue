<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/y/y78brmb1h.css';
import '../../css/w/w1mopgz2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="y78brmb1h"/><path clip-rule="evenodd" class="w1mopgz2k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:open-sidebar-alt-solid" /></template>
