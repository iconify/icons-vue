<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lae2_dgov.css';
import '../../css/a/ah8_uokdg.css';
import '../../css/n/nunhi4evw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lae2_dgov"/><path class="ah8_uokdg"/><path class="nunhi4evw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:price-down-20" /></template>
