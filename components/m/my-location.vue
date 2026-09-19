<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5yh1abav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":472,"height":480};
const content = `<path class="b5yh1abav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:my-location" /></template>
