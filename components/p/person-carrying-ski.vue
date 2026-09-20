<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ytff_t6vw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ytff_t6vw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-carrying-ski" /></template>
