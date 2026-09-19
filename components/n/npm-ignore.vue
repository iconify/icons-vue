<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cvcq89ble.css';
import '../../css/g/gwcu8infc.css';
import '../../css/w/wnfssjrql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cvcq89ble"><path class="gwcu8infc"/><path class="wnfssjrql"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:npm-ignore" /></template>
