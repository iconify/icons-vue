<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/gv7df2j7x.css';
import '../../css/z/zfqr1nk8b.css';
import '../../css/w/w49j0rbvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVGWERm2vsw"><g class="ft5dv1b6b"><path class="gv7df2j7x"/><path class="zfqr1nk8b"/></g></mask></defs><path mask="url(#SVGWERm2vsw)" class="w49j0rbvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:ticket-alt-duotone-line" /></template>
