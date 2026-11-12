<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bf-mlm0al.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bf-mlm0al"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:smartfox-dark" /></template>
