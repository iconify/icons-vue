<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j1_z_4b0d.css';
import '../../css/t/t7kmc2bkf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j1_z_4b0d"/><path class="t7kmc2bkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:package-dependents-24" /></template>
