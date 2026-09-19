<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ew3xsfbas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ew3xsfbas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:mobile-phone-alt" /></template>
