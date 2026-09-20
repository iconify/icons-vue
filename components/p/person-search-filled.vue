<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lv85zh.css';
import '../../css/t/t5pxry.css';
import '../../css/c/cmsyud.css';
import '../../css/s/s8e22g.css';
import '../../css/s/sur8om.css';
import '../../css/y/ydovum.css';
import '../../css/l/lsejuv.css';
import '../../css/y/yk_w1o.css';
import '../../css/o/o0bcgl.css';
import '../../css/s/so-to-0.css';
import '../../css/f/fill-to-1.css';
import '../../css/f/fade-to-1.css';
import '../../css/s/so-from-22.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVGem1WcmEr"><path class="lv85zh t5pxry"/><path class="cmsyud"/></mask></defs><path class="s8e22g sur8om t5pxry ydovum"/><path mask="url(#SVGem1WcmEr)" class="lsejuv ydovum"/><path class="s8e22g t5pxry ydovum yk_w1o"/><path class="o0bcgl s8e22g t5pxry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:person-search-filled" /></template>
