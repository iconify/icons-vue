<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/y/yk_lkmb7k.css';
import '../../css/v/v6k-1zb2k.css';
import '../../css/s/sj6ssgzvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="yk_lkmb7k"/><path class="v6k-1zb2k"/><path class="sj6ssgzvr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:programming-language-browser-css" /></template>
