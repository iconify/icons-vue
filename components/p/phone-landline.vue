<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r0v05y64m.css';
import '../../css/a/adgg27x9x.css';
import '../../css/t/t3url24-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="r0v05y64m"/><path class="adgg27x9x"/><path class="t3url24-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:phone-landline" /></template>
