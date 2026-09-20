<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j3oyjbb4p.css';
import '../../css/e/e56i_o0sr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="j3oyjbb4p"/><path class="e56i_o0sr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:usb-cable-solid" /></template>
