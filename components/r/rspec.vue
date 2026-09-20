<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dzghodlei.css';
import '../../css/f/f9yyg-b3m.css';
import '../../css/u/uys2z4s7k.css';
import '../../css/r/r1tlpd6cz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="dzghodlei"/><path class="f9yyg-b3m"/><path class="uys2z4s7k"/><path class="r1tlpd6cz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:rspec" /></template>
