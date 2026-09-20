<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/w/wwoto2b7e.css';
import '../../css/o/ol9y5c9kd.css';
import '../../css/w/w3exxgbev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="wwoto2b7e"/><path class="ol9y5c9kd"/><path class="w3exxgbev"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp-color:router-wifi-network-flat" /></template>
