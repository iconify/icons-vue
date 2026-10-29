<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/h/hbyi_obok.css';
import '../../css/b/b6acjm45t.css';
import '../../css/f/f6_0b0b7v.css';
import '../../css/m/mq3osobty.css';
import '../../css/n/nej6xhpny.css';
import '../../css/d/dp_gv7bnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="hbyi_obok wm-deco"/><path class="b6acjm45t wm-deco"/><path class="f6_0b0b7v wm-deco"/><path class="mq3osobty wm-k"/><path class="nej6xhpny wm-a"/><path class="dp_gv7bnq wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:thumbs-up-blueprint" /></template>
