<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/z/z-3_bibib.css';
import '../../css/w/w_5heldpj.css';
import '../../css/i/iwf9cnu_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z-3_bibib"/><path class="w_5heldpj"/><path class="iwf9cnu_o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:message-edit" /></template>
