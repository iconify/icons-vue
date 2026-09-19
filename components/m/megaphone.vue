<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jsb0x-bvb.css';
import '../../css/q/q5st0_sjt.css';
import '../../css/e/ex6kq6bjn.css';
import '../../css/k/khx7cwb3l.css';
import '../../css/e/ewm16cc7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jsb0x-bvb"/><path class="q5st0_sjt"/><path class="ex6kq6bjn"/><path class="khx7cwb3l"/><path class="ewm16cc7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:megaphone" /></template>
