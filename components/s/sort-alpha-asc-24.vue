<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mnp81lbbc.css';
import '../../css/o/odno2sboo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mnp81lbbc"/><path class="odno2sboo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:sort-alpha-asc-24" /></template>
