<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udl_y2bcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="udl_y2bcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-boarding-ferryboat" /></template>
