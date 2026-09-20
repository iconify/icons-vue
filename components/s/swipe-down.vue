<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/br909-7ad.css';
import '../../css/x/x4u8pbwjc.css';
import '../../css/l/l11ab0b0r.css';
import '../../css/j/jy2e39b0o.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/q/q-k8f2ewt.css';
import '../../css/i/it_-3rr0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<circle class="br909-7ad"/><g class="x4u8pbwjc"><path class="l11ab0b0r"/><path class="jy2e39b0o"/></g><g class="jn8qy4bru"><path class="q-k8f2ewt"/><path class="it_-3rr0c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:swipe-down" /></template>
