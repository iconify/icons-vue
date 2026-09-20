<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/opmrojb7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="opmrojb7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ynab-light" /></template>
