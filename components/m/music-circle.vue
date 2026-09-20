<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/t/t9rbyychv.css';
import '../../css/e/eo22vc03g.css';
import '../../css/g/gz6xmvf9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t9rbyychv"/><path class="eo22vc03g"/><path class="gz6xmvf9a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:music-circle" /></template>
