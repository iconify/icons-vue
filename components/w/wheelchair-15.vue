<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m88vfibvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="m88vfibvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:wheelchair-15" /></template>
