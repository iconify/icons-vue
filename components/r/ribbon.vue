<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/b/bf5_xfbow.css';
import '../../css/d/die8b53tm.css';
import '../../css/l/lx9jh7bof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bf5_xfbow"/><path class="die8b53tm"/><path class="lx9jh7bof"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:ribbon" /></template>
