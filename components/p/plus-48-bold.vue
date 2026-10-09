<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v71jzsb3t.css';
import '../../css/i/ilg_98b5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v71jzsb3t"/><path class="ilg_98b5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:plus-48-bold" /></template>
