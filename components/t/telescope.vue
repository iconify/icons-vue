<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/n/nw1o6hbup.css';
import '../../css/r/rtc2vebam.css';
import '../../css/q/qw0rhm64r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nw1o6hbup"/><path class="rtc2vebam"/><circle class="qw0rhm64r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:telescope" /></template>
