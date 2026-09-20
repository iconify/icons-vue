<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kz-xe4l0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kz-xe4l0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tolgee-light" /></template>
