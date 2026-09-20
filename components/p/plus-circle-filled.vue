<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pyx2zp.css';
import '../../css/t/t5pxry.css';
import '../../css/e/ermg4a.css';
import '../../css/u/u63-fz.css';
import '../../css/r/rk72je.css';
import '../../css/b/botfzx.css';
import '../../css/s/so-from-60.css';
import '../../css/f/fill-to-1.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVGOv6HZyWk"><path class="pyx2zp t5pxry"/><path class="ermg4a t5pxry u63-fz"/><path class="rk72je t5pxry u63-fz"/></mask></defs><path mask="url(#SVGOv6HZyWk)" class="botfzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:plus-circle-filled" /></template>
