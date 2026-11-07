<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pv_hji6de.css';
import '../../css/e/eaqdpdd8a.css';
import '../../css/n/nr40y6jfb.css';
import '../../css/i/ia8kjfbpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pv_hji6de"/><path class="eaqdpdd8a"/><path class="nr40y6jfb"/><path class="ia8kjfbpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sort-bold-duotone" /></template>
