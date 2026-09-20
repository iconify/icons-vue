<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/onraaob_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="onraaob_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:screen-alt-outline" /></template>
