<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qs_b2rwwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qs_b2rwwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:user-management-filled" /></template>
