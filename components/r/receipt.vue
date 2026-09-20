<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtowsomii.css';
import '../../css/n/n4wg8hb7c.css';
import '../../css/i/iuoe8u8la.css';
import '../../css/w/w41tqmb-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<g class="jtowsomii"><path class="n4wg8hb7c"/><path class="iuoe8u8la"/><path class="w41tqmb-r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:receipt" /></template>
