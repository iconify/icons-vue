<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/z/z08-9pbuq.css';
import '../../css/z/z3cyn9bdw.css';
import '../../css/s/st6veybqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z08-9pbuq"/><path class="z3cyn9bdw"/><path class="st6veybqt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:users-round" /></template>
