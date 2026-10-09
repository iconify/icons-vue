<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pmov8hb-b.css';
import '../../css/m/mn4wyfb1u.css';
import '../../css/a/anwbogkuk.css';
import '../../css/x/xog6z1bwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pmov8hb-b"/><path class="mn4wyfb1u"/><path class="anwbogkuk"/><path class="xog6z1bwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:store-48-bold" /></template>
