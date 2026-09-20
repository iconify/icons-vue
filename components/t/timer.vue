<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/b/bwjoyu67r.css';
import '../../css/f/fhcsjwttb.css';
import '../../css/x/x-adczucl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="bwjoyu67r"/><circle class="fhcsjwttb"/><path class="x-adczucl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:timer" /></template>
