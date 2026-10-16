<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/plymhoh3i.css';
import '../../css/d/dxxr-08um.css';
import '../../css/p/pbcox6rvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="plymhoh3i"/><path class="dxxr-08um"/><path class="pbcox6rvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:power-restore-20" /></template>
