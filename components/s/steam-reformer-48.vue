<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/asop52brs.css';
import '../../css/p/pio8nkbyn.css';
import '../../css/h/hiktgyb7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="asop52brs"/><path class="pio8nkbyn"/><path class="hiktgyb7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:steam-reformer-48" /></template>
