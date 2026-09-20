<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/y/yian4bcbi.css';
import '../../css/p/phelvmbqn.css';
import '../../css/h/hj977r91q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="yian4bcbi"/><path class="phelvmbqn"/><path class="hj977r91q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp-color:screen-tv-flat" /></template>
