<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o5siuz3mb.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/t/tfazt4b9n.css';
import '../../css/d/d2mg5e3yn.css';
import '../../css/p/p1ab4zb0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o5siuz3mb secondary"/><g class="dt0cm9dhy primary"><path class="tfazt4b9n"/><circle class="d2mg5e3yn"/><path class="p1ab4zb0b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:passport-duo" /></template>
