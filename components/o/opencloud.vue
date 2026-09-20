<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bnzwy0uxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bnzwy0uxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:opencloud" /></template>
