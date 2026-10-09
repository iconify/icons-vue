<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vfpjugbvy.css';
import '../../css/b/blnw30haf.css';
import '../../css/f/fox5ysyus.css';
import '../../css/k/kurs2nb8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vfpjugbvy"/><path class="blnw30haf"/><path class="fox5ysyus"/><path class="kurs2nb8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:smart-home-48-bold" /></template>
