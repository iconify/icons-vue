<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xtmuzrg2o.css';
import '../../css/v/v35_57ben.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xtmuzrg2o"/><path clip-rule="evenodd" class="v35_57ben"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:text-bold-circle-bold-duotone" /></template>
