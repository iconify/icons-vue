<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r0k19hilo.css';
import '../../css/p/ps9svrb0r.css';
import '../../css/n/niyv1hwum.css';
import '../../css/r/rj41gebbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r0k19hilo"/><path class="ps9svrb0r"/><path class="niyv1hwum"/><path class="rj41gebbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:shovel-48-bold" /></template>
