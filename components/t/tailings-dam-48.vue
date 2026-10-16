<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tjbhs-95h.css';
import '../../css/z/zns5-suvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tjbhs-95h"/><path class="zns5-suvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tailings-dam-48" /></template>
