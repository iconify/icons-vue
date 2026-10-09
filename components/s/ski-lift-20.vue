<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ox-4if7um.css';
import '../../css/l/ld9a8ebwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ox-4if7um"/><path class="ld9a8ebwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ski-lift-20" /></template>
