<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/l/lh2s7ebjn.css';
import '../../css/s/saewjvbbt.css';
import '../../css/w/w4e8ihwgt.css';
import '../../css/d/d_-dzx7jm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="lh2s7ebjn wm-shadow"/><path class="saewjvbbt wm-shadow"/><path class="w4e8ihwgt"/><path class="d_-dzx7jm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:switch-camera" /></template>
