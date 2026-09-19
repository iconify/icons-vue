<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f01n6jbsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f01n6jbsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:pointing-right-08" /></template>
