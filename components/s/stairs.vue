<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kz8qy3bgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":63,"height":64};
const content = `<path class="kz8qy3bgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:stairs" /></template>
