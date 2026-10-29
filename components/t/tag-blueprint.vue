<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/n/nxw6p7baq.css';
import '../../css/g/go5p0wb8r.css';
import '../../css/i/ibni4opcv.css';
import '../../css/k/k-o29k8-z.css';
import '../../css/e/e61c4pwgm.css';
import '../../css/r/rw8j70bno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="nxw6p7baq wm-deco"/><path class="go5p0wb8r wm-deco"/><path class="ibni4opcv wm-deco"/><path class="k-o29k8-z wm-k"/><path class="e61c4pwgm wm-a"/><path class="rw8j70bno wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:tag-blueprint" /></template>
