<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/m/mcovfn7ky.css';
import '../../css/z/z1rrn3z9c.css';
import '../../css/a/absczkmyl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="mcovfn7ky"/><path class="wm-k z1rrn3z9c"/><path class="absczkmyl wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:speaker-sketch" /></template>
