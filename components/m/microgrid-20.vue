<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/thf03bbvf.css';
import '../../css/i/i1ehzlbeu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="thf03bbvf"/><path class="i1ehzlbeu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:microgrid-20" /></template>
