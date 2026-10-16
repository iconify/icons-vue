<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tsmhpgwcs.css';
import '../../css/c/c_1sw_nww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tsmhpgwcs"/><path class="c_1sw_nww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:picture-in-picture-48" /></template>
