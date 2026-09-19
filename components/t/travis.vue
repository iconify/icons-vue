<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wxewg8z1p.css';
import '../../css/t/t08ue7k0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wxewg8z1p"/><path class="t08ue7k0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:travis" /></template>
