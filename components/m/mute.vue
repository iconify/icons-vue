<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oflhhkbur.css';
import '../../css/r/rql-eabty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="oflhhkbur"/><path class="rql-eabty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:mute" /></template>
