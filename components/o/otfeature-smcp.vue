<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gbv9oaccb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="gbv9oaccb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:otfeature-smcp" /></template>
