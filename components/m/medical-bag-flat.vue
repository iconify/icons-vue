<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/k/kn0lpk9fb.css';
import '../../css/q/qclqxdbjb.css';
import '../../css/k/kqadjqbqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="kn0lpk9fb"/><path class="qclqxdbjb"/><path class="kqadjqbqh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:medical-bag-flat" /></template>
