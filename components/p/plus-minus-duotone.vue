<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/f44_mnbui.css';
import '../../css/k/kxm009byi.css';
import '../../css/z/zb5u0ulau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="f44_mnbui"/><path class="kxm009byi"/><path clip-rule="evenodd" class="zb5u0ulau"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:plus-minus-duotone" /></template>
