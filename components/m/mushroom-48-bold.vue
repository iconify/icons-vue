<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g15nsgp2r.css';
import '../../css/a/at_nf4hhp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g15nsgp2r"/><path class="at_nf4hhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:mushroom-48-bold" /></template>
