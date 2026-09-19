<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/fnqpwbr3p.css';
import '../../css/q/qvehglxch.css';
import '../../css/s/sktif2b-h.css';
import '../../css/e/eux4w11sh.css';
import '../../css/m/mibfyyx9o.css';
import '../../css/m/mk4ttky0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="fnqpwbr3p"/><path class="qvehglxch"/><path clip-rule="evenodd" class="sktif2b-h"/><path class="eux4w11sh"/><path class="mibfyyx9o"/><path clip-rule="evenodd" class="mk4ttky0o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:satellite-outline" /></template>
