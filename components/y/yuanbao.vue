<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rw1pi9cpe.css';
import '../../css/l/ldcc6fbjt.css';
import '../../css/i/in_j66beg.css';
import '../../css/p/psw28h88l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rw1pi9cpe"/><path class="ldcc6fbjt"/><path class="in_j66beg"/><path class="psw28h88l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:yuanbao" /></template>
