<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ee8z-20zw.css';
import '../../css/m/m-327hb7l.css';
import '../../css/q/qpyv20i8g.css';
import '../../css/l/ljqckqbpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ee8z-20zw"/><path class="m-327hb7l"/><path class="qpyv20i8g"/><path class="ljqckqbpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:wliti" /></template>
