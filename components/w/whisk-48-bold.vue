<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vm3_6xbay.css';
import '../../css/w/w9clkgbaa.css';
import '../../css/b/bcto3bbby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vm3_6xbay"/><path class="w9clkgbaa"/><path class="bcto3bbby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:whisk-48-bold" /></template>
