<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/ixat7proj.css';
import '../../css/l/lyvxmduej.css';
import '../../css/m/m63f0bc6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ixat7proj"/><path clip-rule="evenodd" class="lyvxmduej"/><path class="m63f0bc6j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:school-flag-alt-solid" /></template>
