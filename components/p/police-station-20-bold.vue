<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fbn8jqf1h.css';
import '../../css/b/b0cn2mb5s.css';
import '../../css/c/ct59a3bzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fbn8jqf1h"/><path class="b0cn2mb5s"/><path class="ct59a3bzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:police-station-20-bold" /></template>
