<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/v/vch52gryj.css';
import '../../css/w/wkpyxkb9o.css';
import '../../css/w/w31z-ubuz.css';
import '../../css/n/ntxd9m1mx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="vch52gryj"/><path class="wkpyxkb9o"/><path class="w31z-ubuz"/><path class="ntxd9m1mx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:playlist-menu" /></template>
