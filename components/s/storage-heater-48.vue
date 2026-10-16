<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/acm28njiw.css';
import '../../css/w/w31w9xbxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="acm28njiw"/><path class="w31w9xbxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:storage-heater-48" /></template>
