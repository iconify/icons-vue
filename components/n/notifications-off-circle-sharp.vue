<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tdyizyb3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tdyizyb3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:notifications-off-circle-sharp" /></template>
