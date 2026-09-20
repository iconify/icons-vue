<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/r/r9r1ddcku.css';
import '../../css/a/a_eosd8fx.css';
import '../../css/q/q277pjbhm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="r9r1ddcku"/><path class="a_eosd8fx"/><path class="q277pjbhm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:strawberry-flat" /></template>
