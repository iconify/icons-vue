<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yo_vedc_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yo_vedc_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mailpit-dark" /></template>
