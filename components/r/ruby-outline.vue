<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wiw_s6b9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wiw_s6b9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:ruby-outline" /></template>
