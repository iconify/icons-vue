<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qe5dr5b9o.css';
import '../../css/h/hsqpd_2br.css';
import '../../css/a/anzwqbcxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qe5dr5b9o"/><path class="hsqpd_2br"/><path class="anzwqbcxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:webpack" /></template>
