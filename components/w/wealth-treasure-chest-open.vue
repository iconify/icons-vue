<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/o/o-0s74bqa.css';
import '../../css/l/l6hbmybvh.css';
import '../../css/o/o9d9mccyf.css';
import '../../css/c/ca9jddbuc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="o-0s74bqa"/><path class="l6hbmybvh"/><path class="o9d9mccyf"/><path class="ca9jddbuc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:wealth-treasure-chest-open" /></template>
