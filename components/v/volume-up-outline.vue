<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mit5m27lp.css';
import '../../css/g/gv9g0dbfb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mit5m27lp"/><path class="gv9g0dbfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:volume-up-outline" /></template>
