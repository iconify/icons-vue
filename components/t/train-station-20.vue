<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v87_h9jef.css';
import '../../css/k/kb-m8o5vb.css';
import '../../css/v/vm-u7rbby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="v87_h9jef"/><path class="kb-m8o5vb"/><path class="vm-u7rbby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:train-station-20" /></template>
