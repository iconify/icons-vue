<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/h/h6-dx1i7u.css';
import '../../css/x/x1_l6dbyq.css';
import '../../css/s/s9oud4b4r.css';
import '../../css/m/mmk0geb0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="h6-dx1i7u"/><path class="x1_l6dbyq"/><path class="s9oud4b4r"/><path class="mmk0geb0u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:plug-socket" /></template>
