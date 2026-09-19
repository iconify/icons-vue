<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/r/rzkg9v93r.css';
import '../../css/v/v3g6xoxym.css';
import '../../css/k/ksnlu0kra.css';
import '../../css/a/apvj7jbhz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="rzkg9v93r"/><circle class="v3g6xoxym"/><path class="ksnlu0kra"/><path class="apvj7jbhz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:sickbed" /></template>
