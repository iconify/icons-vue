<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/v/v6epoi7eh.css';
import '../../css/v/vze4wuf6n.css';
import '../../css/k/k6tf0lb3j.css';
import '../../css/g/gdif04buu.css';
import '../../css/d/da8zwfb5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="v6epoi7eh wm-deco"/><path class="vze4wuf6n wm-deco"/><path class="k6tf0lb3j wm-k"/><path class="gdif04buu wm-a"/><path class="da8zwfb5x wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:monitor-blueprint" /></template>
