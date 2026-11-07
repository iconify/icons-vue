<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/isvst5k4t.css';
import '../../css/m/mm5l9hb-p.css';
import '../../css/o/ovgsf7b1z.css';
import '../../css/j/j1tvjbbgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="isvst5k4t"/><path clip-rule="evenodd" class="mm5l9hb-p"/><path clip-rule="evenodd" class="ovgsf7b1z"/><path class="j1tvjbbgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:user-speak-outline" /></template>
