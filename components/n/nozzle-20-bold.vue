<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ev392zb0m.css';
import '../../css/i/iusq5pwib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ev392zb0m"/><path class="iusq5pwib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:nozzle-20-bold" /></template>
