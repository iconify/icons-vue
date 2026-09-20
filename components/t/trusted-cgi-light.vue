<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqm3jdo2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kqm3jdo2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:trusted-cgi-light" /></template>
