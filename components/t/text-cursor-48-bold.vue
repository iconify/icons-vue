<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wkh-90byk.css';
import '../../css/x/x-e0pwbux.css';
import '../../css/s/s20085b2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wkh-90byk"/><path class="x-e0pwbux"/><path class="s20085b2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:text-cursor-48-bold" /></template>
