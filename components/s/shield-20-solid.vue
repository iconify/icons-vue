<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lra8npb0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lra8npb0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:shield-20-solid" /></template>
