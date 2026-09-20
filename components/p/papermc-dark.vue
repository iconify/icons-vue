<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/spvsfy5mn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="spvsfy5mn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:papermc-dark" /></template>
