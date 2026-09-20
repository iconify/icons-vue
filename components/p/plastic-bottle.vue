<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2h8hw-en.css';
import '../../css/t/tprn25b3b.css';
import '../../css/u/uqie46eea.css';
import '../../css/j/jn8cixsry.css';
import '../../css/p/p23naccen.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="d2h8hw-en"/><rect class="tprn25b3b"/><path class="uqie46eea"/><path class="jn8cixsry"/><path class="p23naccen"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:plastic-bottle" /></template>
