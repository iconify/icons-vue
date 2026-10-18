<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xszfmab4u.css';
import '../../css/h/hutzz7vvf.css';
import '../../css/b/b-qq9xb5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xszfmab4u"/><path class="hutzz7vvf"/><path class="b-qq9xb5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:solar-monitoring-48" /></template>
