<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n4aitobkj.css';
import '../../css/w/w33pk5bec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n4aitobkj"/><path class="w33pk5bec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:text-search-48-bold" /></template>
