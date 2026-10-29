<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/l/l4wrd57_f.css';
import '../../css/t/t_qq9wb5b.css';
import '../../css/z/za0qrbr5b.css';
import '../../css/q/qtot5zs0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="l4wrd57_f wm-k"/><path class="t_qq9wb5b wm-a"/><path class="wm-k za0qrbr5b"/><path class="qtot5zs0c wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:tent-sketch" /></template>
