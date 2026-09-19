<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j9-6onlzi.css';
import '../../css/i/i7dr051db.css';
import '../../css/q/qe60n2b7a.css';
import '../../css/e/ejdenbgzh.css';
import '../../css/m/m6tc1nb3o.css';
import '../../css/g/g-0_lkbmi.css';
import '../../css/i/ijnc63qbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j9-6onlzi"/><path class="i7dr051db"/><path class="qe60n2b7a"/><path class="ejdenbgzh"/><path class="m6tc1nb3o"/><path class="g-0_lkbmi"/><path class="ijnc63qbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:milkyway" /></template>
