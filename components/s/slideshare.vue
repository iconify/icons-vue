<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nd665b1nm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nd665b1nm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo-social:slideshare" /></template>
