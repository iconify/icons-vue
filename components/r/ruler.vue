<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/pl10uib_z.css';
import '../../css/m/md-hw5o0n.css';
import '../../css/i/ic5x_6btl.css';
import '../../css/j/jimwxrbhg.css';
import '../../css/u/ui99pgbbf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="pl10uib_z wm-k"/><path class="md-hw5o0n wm-k"/><path class="ic5x_6btl wm-k"/><path class="jimwxrbhg wm-shine"/><path class="ui99pgbbf wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-anime:ruler" /></template>
