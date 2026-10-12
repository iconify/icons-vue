<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/clchgpbjo.css';
import '../../css/q/qvo2fwbpx.css';
import '../../css/r/rmh8yimxi.css';
import '../../css/w/wq8vaxb7s.css';
import '../../css/s/sfb8rqn9v.css';
import '../../css/k/ksydp3lsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="clchgpbjo"/><path class="qvo2fwbpx"/><path class="rmh8yimxi"/><path class="wq8vaxb7s"/><path class="sfb8rqn9v"/><path class="ksydp3lsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:smart-meter-x-48-bold" /></template>
