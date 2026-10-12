<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ta5f1hbwd.css';
import '../../css/r/r-bb6_b2h.css';
import '../../css/e/ehrnxuvhv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ta5f1hbwd"/><path class="r-bb6_b2h"/><path class="ehrnxuvhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pig-48-bold" /></template>
