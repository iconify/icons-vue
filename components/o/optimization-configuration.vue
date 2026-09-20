<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/x/xqkznob5a.css';
import '../../css/z/z8ec_ubvd.css';
import '../../css/l/l4do04bvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="xqkznob5a"/><path class="z8ec_ubvd"/><path class="l4do04bvm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:optimization-configuration" /></template>
