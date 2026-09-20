<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hradzg3vi.css';
import '../../css/n/norpj8pcf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hradzg3vi"/><path class="norpj8pcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:raygun-monitoring-dark" /></template>
