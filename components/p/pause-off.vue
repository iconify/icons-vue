<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c5xdmn.css';
import '../../css/y/yxu38m.css';
import '../../css/z/zxndow.css';
import '../../css/s/sxex9y.css';
import '../../css/l/lvtybe.css';
import '../../css/o/oxx-om.css';
import '../../css/b/botfzx.css';
import '../../css/g/gd_4-q.css';
import '../../css/s/so-from-30.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVGnTzHEi9Z"><path class="c5xdmn yxu38m zxndow"/><path class="c5xdmn sxex9y zxndow"/><path class="c5xdmn lvtybe oxx-om"/></mask></defs><path mask="url(#SVGnTzHEi9Z)" class="botfzx"/><path class="c5xdmn gd_4-q lvtybe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:pause-off" /></template>
