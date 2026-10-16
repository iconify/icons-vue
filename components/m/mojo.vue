<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gvbimsl5a.css';
import '../../css/p/pk3csccbi.css';
import '../../css/r/ru0jvrb6y.css';
import '../../css/b/bv63s8ozg.css';
import '../../css/h/hzx_h6b0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":19.5,"height":26,"left":61.5,"top":2};
const content = `<path class="gvbimsl5a"/><path class="pk3csccbi"/><path class="ru0jvrb6y"/><path class="bv63s8ozg"/><path class="hzx_h6b0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:mojo" /></template>
