<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnk58xbgu.css';
import '../../css/i/ifbfh7xzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rnk58xbgu"/><path class="ifbfh7xzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:waypoints-48-bold" /></template>
