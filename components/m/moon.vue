<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t6i_d-b2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t6i_d-b2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:moon" /></template>
