<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/p/p4937g1yq.css';
import '../../css/e/etvrawbsd.css';
import '../../css/v/vlzselbkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p4937g1yq"/><path class="etvrawbsd"/><path class="vlzselbkt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:search-user" /></template>
