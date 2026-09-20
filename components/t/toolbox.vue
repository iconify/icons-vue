<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gh__tacrr.css';
import '../../css/q/qhgqg5brt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gh__tacrr"/><path class="qhgqg5brt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:toolbox" /></template>
