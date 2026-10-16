<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/osf7zog9q.css';
import '../../css/h/h818ewufo.css';
import '../../css/k/krsiqfbpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="osf7zog9q"/><path class="h818ewufo"/><path class="krsiqfbpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tokamak-48-bold" /></template>
