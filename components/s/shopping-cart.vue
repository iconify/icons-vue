<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/c/c35fhsbht.css';
import '../../css/m/mbjtpbb8u.css';
import '../../css/o/o8hc6nb6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="c35fhsbht"/><circle class="mbjtpbb8u"/><circle class="o8hc6nb6w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:shopping-cart" /></template>
