<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/m/m8am-9box.css';
import '../../css/h/hav_9b5ms.css';
import '../../css/m/mrlb7pzin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="m8am-9box"/><path class="hav_9b5ms"/><path class="mrlb7pzin"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:settings-error-01" /></template>
