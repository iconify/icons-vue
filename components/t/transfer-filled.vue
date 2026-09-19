<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/u/uhzia1c2l.css';
import '../../css/j/j22be9bvi.css';
import '../../css/w/w308kqbvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="uhzia1c2l"/><path class="j22be9bvi"/><path class="w308kqbvw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:transfer-filled" /></template>
