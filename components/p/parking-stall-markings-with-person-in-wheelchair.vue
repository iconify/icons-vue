<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mr_dv5t7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="mr_dv5t7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:parking-stall-markings-with-person-in-wheelchair" /></template>
