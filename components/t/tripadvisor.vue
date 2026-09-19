<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oz_tv8bwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="oz_tv8bwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:tripadvisor" /></template>
