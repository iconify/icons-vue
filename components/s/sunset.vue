<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/c/cwkyo5bfm.css';
import '../../css/v/vca6n0zbn.css';
import '../../css/t/tm3o10moh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="cwkyo5bfm"/><path class="vca6n0zbn"/><circle class="tm3o10moh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:sunset" /></template>
