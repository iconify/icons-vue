<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/hzl37klcf.css';
import '../../css/t/tlzl36baj.css';
import '../../css/o/oasgoj2dk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<g class="cuyn6tgcc"><path class="hzl37klcf"/><path class="tlzl36baj"/><path class="oasgoj2dk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:odnoklassniki-circle" /></template>
