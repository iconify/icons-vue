<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpjd-ub0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="lpjd-ub0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:uni5475-box-filled" /></template>
