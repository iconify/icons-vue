<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i5i-ymejz.css';
import '../../css/x/xv-3bjb_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i5i-ymejz"/><path class="xv-3bjb_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:rotor-48" /></template>
