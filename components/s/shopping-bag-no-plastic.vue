<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/a/ak298ni-i.css';
import '../../css/x/xu1hxdbwb.css';
import '../../css/e/e1kbs5w7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="ak298ni-i"/><path class="xu1hxdbwb"/><path class="e1kbs5w7c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:shopping-bag-no-plastic" /></template>
