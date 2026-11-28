<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cgv4zmqct.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/u/ud95brdct.css';
import '../../css/o/o6pz2hves.css';
import '../../css/n/nkt1nybhp.css';
import '../../css/l/lidtypbmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cgv4zmqct secondary"/><g class="dt0cm9dhy primary"><path class="ud95brdct"/><path class="o6pz2hves"/><path class="nkt1nybhp"/><path class="lidtypbmg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:vinyl-duo" /></template>
