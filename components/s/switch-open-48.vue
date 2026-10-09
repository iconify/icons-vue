<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-dmmacii.css';
import '../../css/b/bo2mh3bzn.css';
import '../../css/u/ua8x71bme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j-dmmacii"/><path class="bo2mh3bzn"/><path class="ua8x71bme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:switch-open-48" /></template>
