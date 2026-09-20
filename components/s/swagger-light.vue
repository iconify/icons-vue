<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zjmofvbbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zjmofvbbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:swagger-light" /></template>
