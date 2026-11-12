<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hvmnxt6ft.css';
import '../../css/m/mkor83bnq.css';
import '../../css/m/m8r9zubhb.css';
import '../../css/y/y1mciqk_m.css';
import '../../css/d/dbqjt5bjh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hvmnxt6ft"/><path class="mkor83bnq"/><path class="m8r9zubhb"/><path class="y1mciqk_m"/><path class="dbqjt5bjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-excel-light" /></template>
