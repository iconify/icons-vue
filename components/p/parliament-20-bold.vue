<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xkzmacc8l.css';
import '../../css/a/a4qgedb8h.css';
import '../../css/t/ta45wzagz.css';
import '../../css/y/yfoxxnbix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xkzmacc8l"/><path class="a4qgedb8h"/><path class="ta45wzagz"/><path class="yfoxxnbix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:parliament-20-bold" /></template>
