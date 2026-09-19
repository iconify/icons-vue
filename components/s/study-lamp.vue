<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/f/fd7fxu0eo.css';
import '../../css/g/geplcma4c.css';
import '../../css/b/bwm5pk45n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="fd7fxu0eo"/><path class="geplcma4c"/><path class="bwm5pk45n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:study-lamp" /></template>
