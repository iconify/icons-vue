<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/un_01ximz.css';
import '../../css/m/m4rbgbbhm.css';
import '../../css/q/qzowdsb6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="un_01ximz"/><path class="m4rbgbbhm"/><path class="qzowdsb6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:phone-outgoing-48" /></template>
