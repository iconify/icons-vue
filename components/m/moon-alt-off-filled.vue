<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pggcet.css';
import '../../css/t/t5pxry.css';
import '../../css/z/zxndow.css';
import '../../css/m/m9pw2i.css';
import '../../css/y/y4wbml.css';
import '../../css/z/zac2_x.css';
import '../../css/n/npdh_t.css';
import '../../css/c/chf8aj.css';
import '../../css/i/i_5n8q.css';
import '../../css/o/oxx-om.css';
import '../../css/b/botfzx.css';
import '../../css/g/gd_4-q.css';
import '../../css/s/so-from-56.css';
import '../../css/f/fill-to-1.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVGgo4DocDQ"><path class="pggcet t5pxry zxndow"/><path class="m9pw2i y4wbml zac2_x zxndow"/><path class="m9pw2i npdh_t y4wbml zxndow"/><path class="chf8aj m9pw2i y4wbml zxndow"/><path class="i_5n8q oxx-om t5pxry y4wbml"/></mask></defs><path mask="url(#SVGgo4DocDQ)" class="botfzx"/><path class="gd_4-q i_5n8q t5pxry y4wbml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:moon-alt-off-filled" /></template>
