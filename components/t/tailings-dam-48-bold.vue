<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/it4grp-4n.css';
import '../../css/h/hk3jr4mxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="it4grp-4n"/><path class="hk3jr4mxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tailings-dam-48-bold" /></template>
