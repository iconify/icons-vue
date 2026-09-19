<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gda_39avp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gda_39avp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:peoples" /></template>
