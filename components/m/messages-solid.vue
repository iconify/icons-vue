<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/s/s5r365bol.css';
import '../../css/u/uw9crg0us.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="s5r365bol"/><path class="uw9crg0us"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:messages-solid" /></template>
