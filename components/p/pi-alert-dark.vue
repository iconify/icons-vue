<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t9hz5nq9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t9hz5nq9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pi-alert-dark" /></template>
