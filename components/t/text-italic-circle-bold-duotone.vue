<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xtmuzrg2o.css';
import '../../css/m/mmtd6l_0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xtmuzrg2o"/><path class="mmtd6l_0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:text-italic-circle-bold-duotone" /></template>
