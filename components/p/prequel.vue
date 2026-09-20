<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fl1cnobzu.css';
import '../../css/q/qgzh5-i-h.css';
import '../../css/o/ozav58bde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fl1cnobzu"/><circle class="qgzh5-i-h"/><circle class="ozav58bde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:prequel" /></template>
