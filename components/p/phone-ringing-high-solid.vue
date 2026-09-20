<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ax1grob-r.css';
import '../../css/x/x97sh721c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ax1grob-r"/><path class="x97sh721c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:phone-ringing-high-solid" /></template>
