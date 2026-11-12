<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iufm3lbgw.css';
import '../../css/i/i8odlzb7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iufm3lbgw"/><path class="i8odlzb7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:raygun-monitoring-dark" /></template>
