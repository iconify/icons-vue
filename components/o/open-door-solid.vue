<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/c_r5g1gmo.css';
import '../../css/a/alvqm6bnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="c_r5g1gmo"/><path clip-rule="evenodd" class="alvqm6bnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:open-door-solid" /></template>
