<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w0-a1391i.css';
import '../../css/a/a8ib1rb2l.css';
import '../../css/h/h0q19snmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w0-a1391i"/><path class="a8ib1rb2l"/><path class="h0q19snmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:smart-charging-48-bold" /></template>
