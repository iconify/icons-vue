<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/j/j-wm-8r3v.css';
import '../../css/b/b34n1w8cn.css';
import '../../css/s/sslwlcb4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="j-wm-8r3v"/><path class="b34n1w8cn"/><path class="sslwlcb4r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:programming-language-browser-html" /></template>
