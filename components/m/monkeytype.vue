<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a9pqesbwr.css';
import '../../css/e/ejsqasb_h.css';
import '../../css/b/bohr7wxep.css';
import '../../css/h/hxbsfkehs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":300,"height":180};
const content = `<g class="a9pqesbwr"><path class="ejsqasb_h"/><path class="bohr7wxep"/><path class="hxbsfkehs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:monkeytype" /></template>
