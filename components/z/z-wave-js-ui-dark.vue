<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gwxp7xb5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gwxp7xb5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:z-wave-js-ui-dark" /></template>
