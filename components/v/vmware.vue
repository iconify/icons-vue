<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jdhi3-bsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jdhi3-bsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:vmware" /></template>
