<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ge0c7ebqz.css';
import '../../css/d/dabr2tbbh.css';
import '../../css/j/j5ohattzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ge0c7ebqz"/><path clip-rule="evenodd" class="dabr2tbbh"/><path class="j5ohattzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:mortarboard-fill" /></template>
