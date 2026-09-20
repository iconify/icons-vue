<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/h/hn6vjikxi.css';
import '../../css/n/nus4-e6se.css';
import '../../css/d/dm3sohm9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="hn6vjikxi"/><path class="nus4-e6se"/><path class="dm3sohm9v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:shopping-bag-side" /></template>
