<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/z/zmxinbbaj.css';
import '../../css/m/mkvecdb1a.css';
import '../../css/z/z3176dbdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zmxinbbaj"/><path class="mkvecdb1a"/><path class="z3176dbdw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:refresh-alt" /></template>
