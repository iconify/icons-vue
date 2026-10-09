<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q9x5rac2h.css';
import '../../css/o/o63gs7ffv.css';
import '../../css/n/ne8de7own.css';
import '../../css/h/hfvtdh7cx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q9x5rac2h"/><path class="o63gs7ffv"/><path class="ne8de7own"/><path class="hfvtdh7cx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pylon-48-bold" /></template>
