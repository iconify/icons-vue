<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sz-mjf2ti.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/w/wrlcqkbbd.css';
import '../../css/r/rxubgwwby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary sz-mjf2ti"/><g class="dt0cm9dhy primary"><path class="wrlcqkbbd"/><path class="rxubgwwby"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:tv-minimal-duo" /></template>
