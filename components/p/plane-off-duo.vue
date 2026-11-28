<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lskr6z3ls.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/n/n9skr0b7y.css';
import '../../css/j/j8p3ievks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lskr6z3ls secondary"/><g class="dt0cm9dhy primary"><path class="n9skr0b7y"/><path class="j8p3ievks"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:plane-off-duo" /></template>
