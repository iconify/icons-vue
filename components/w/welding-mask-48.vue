<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jmkkkwifn.css';
import '../../css/e/ea_1x7xoc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jmkkkwifn"/><path class="ea_1x7xoc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:welding-mask-48" /></template>
