<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/to-5kdesz.css';
import '../../css/f/fx_ggjqiy.css';
import '../../css/w/wqy3-lbbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="to-5kdesz"><path class="fx_ggjqiy"/><path class="wqy3-lbbu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:scan-alt-light" /></template>
