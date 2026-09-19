<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f9sb1r7in.css';
import '../../css/z/zmirjg79h.css';
import '../../css/b/b6spzmbdx.css';
import '../../css/m/mai5xwbnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="f9sb1r7in"/><path class="zmirjg79h"/><path class="b6spzmbdx"/><path class="mai5xwbnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="geo:ui-earth-east" /></template>
