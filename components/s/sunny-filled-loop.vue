<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dbg05i.css';
import '../../css/i/iw1iew.css';
import '../../css/b/brd35s.css';
import '../../css/y/y4wbml.css';
import '../../css/y/y2t12w.css';
import '../../css/s/so-from-34.css';
import '../../css/f/fill-to-1.css';
import '../../css/t/tr-2c6-rw.css';
import '../../css/f/fade-to-1.css';
import '../../css/d/d-9_o5mj.css';
import '../../css/d/d-s9ijad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dbg05i iw1iew"/><path class="brd35s iw1iew y4wbml"/><path class="iw1iew y2t12w y4wbml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:sunny-filled-loop" /></template>
