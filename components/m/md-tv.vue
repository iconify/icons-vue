<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gt3xe-z1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gt3xe-z1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-tv" /></template>
