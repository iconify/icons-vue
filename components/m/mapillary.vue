<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ot-2adjyt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ot-2adjyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:mapillary" /></template>
