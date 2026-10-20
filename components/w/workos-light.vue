<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smc74qbot.css';
import '../../css/u/u65_2lbpv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":55.4,"height":48};
const content = `<path class="smc74qbot"/><path class="u65_2lbpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:workos-light" /></template>
