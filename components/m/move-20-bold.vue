<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u20py2moy.css';
import '../../css/h/hi068jb0r.css';
import '../../css/u/uajmqugut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="u20py2moy"/><path class="hi068jb0r"/><path class="uajmqugut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:move-20-bold" /></template>
