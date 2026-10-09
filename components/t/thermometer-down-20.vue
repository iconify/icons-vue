<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6zve7bwi.css';
import '../../css/d/dgtzafb0o.css';
import '../../css/y/y81j8fbuw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="x6zve7bwi"/><path class="dgtzafb0o"/><path class="y81j8fbuw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:thermometer-down-20" /></template>
