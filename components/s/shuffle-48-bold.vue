<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t26y-qb5e.css';
import '../../css/p/p6e6b6d8e.css';
import '../../css/v/v03b8abeb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="t26y-qb5e"/><path class="p6e6b6d8e"/><path class="v03b8abeb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:shuffle-48-bold" /></template>
