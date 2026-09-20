<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/x/xd424yelu.css';
import '../../css/d/d8xjnkbxa.css';
import '../../css/w/wwkxdntgn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="xd424yelu"/><path class="d8xjnkbxa"/><path class="wwkxdntgn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:retouch-cut-edit" /></template>
