<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/twwyzac5a.css';
import '../../css/u/u2u1b9bir.css';
import '../../css/g/gwnw5mblv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="twwyzac5a"/><path class="u2u1b9bir"/><path class="gwnw5mblv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:sandwich" /></template>
