<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eiq_gybtr.css';
import '../../css/q/qgwq-wbxv.css';
import '../../css/f/f7ztvmbgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eiq_gybtr"/><path class="qgwq-wbxv"/><path class="f7ztvmbgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:panels-bottom-right-bold-duotone" /></template>
