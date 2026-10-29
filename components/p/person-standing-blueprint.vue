<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/b/b1hnuwbzm.css';
import '../../css/a/arn6ufbls.css';
import '../../css/n/nip8kwy2i.css';
import '../../css/n/nd14wkb4e.css';
import '../../css/x/xk6eoibzj.css';
import '../../css/h/h6o8vv3vu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="b1hnuwbzm wm-deco"/><path class="arn6ufbls wm-deco"/><path class="nip8kwy2i wm-deco"/><path class="nd14wkb4e wm-k"/><path class="wm-a xk6eoibzj"/><path class="h6o8vv3vu wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:person-standing-blueprint" /></template>
