<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tsfv02bvb.css';
import '../../css/n/n_pikq9wt.css';
import '../../css/i/iee3nhbrg.css';
import '../../css/t/tb90g4hyi.css';
import '../../css/h/hmd4bhb2m.css';
import '../../css/b/blvwopbwu.css';
import '../../css/m/mnf89jb6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<circle class="tsfv02bvb"/><path class="n_pikq9wt"/><path class="iee3nhbrg"/><path class="tb90g4hyi"/><path class="hmd4bhb2m"/><path class="blvwopbwu"/><path class="mnf89jb6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:shushing-face" /></template>
