<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ujn-tbcgw.css';
import '../../css/r/r7__an0bz.css';
import '../../css/g/gcjjvpb6i.css';
import '../../css/a/as8ixpmmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ujn-tbcgw"/><path class="r7__an0bz"/><path class="gcjjvpb6i"/><path class="as8ixpmmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:telemetry-20-bold" /></template>
