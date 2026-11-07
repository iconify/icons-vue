<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pr52f_b5y.css';
import '../../css/r/rmixrvbhu.css';
import '../../css/e/et9k69bbo.css';
import '../../css/p/p9t5yfbwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="pr52f_b5y"><path class="rmixrvbhu"/><path class="et9k69bbo"/><path class="p9t5yfbwc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:stars-minimalistic-broken" /></template>
