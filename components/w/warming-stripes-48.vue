<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vjlkw135c.css';
import '../../css/h/hxvilxtxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vjlkw135c"/><path class="hxvilxtxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:warming-stripes-48" /></template>
