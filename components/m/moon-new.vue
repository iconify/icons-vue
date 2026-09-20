<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1njp3l4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v1njp3l4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteocons:moon-new" /></template>
