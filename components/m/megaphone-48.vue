<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gofrhbcai.css';
import '../../css/t/tpe_wnyve.css';
import '../../css/k/kr1msob9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gofrhbcai"/><path class="tpe_wnyve"/><path class="kr1msob9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:megaphone-48" /></template>
