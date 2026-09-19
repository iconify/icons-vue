<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/voozf6bkw.css';
import '../../css/x/xewwv3l1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="voozf6bkw"/><path class="xewwv3l1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:opacity" /></template>
