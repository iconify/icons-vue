<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/d/dyljlcr5k.css';
import '../../css/k/k3l1toopw.css';
import '../../css/j/jy9j1dbzd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dyljlcr5k"/><path class="k3l1toopw"/><path class="jy9j1dbzd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:wheelchair" /></template>
