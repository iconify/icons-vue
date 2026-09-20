<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c54w_tbjw.css';
import '../../css/i/ifd5f2bkp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c54w_tbjw"/><path class="ifd5f2bkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:wave-hand-fill" /></template>
