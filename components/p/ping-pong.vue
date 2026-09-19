<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/wcbvs6dqg.css';
import '../../css/l/luj-d4blw.css';
import '../../css/c/c9zzvw0xs.css';
import '../../css/e/e712djb_x.css';
import '../../css/o/on0k5wc2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="wcbvs6dqg"/><path class="luj-d4blw"/><path class="c9zzvw0xs"/><path class="e712djb_x"/><path class="on0k5wc2e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:ping-pong" /></template>
