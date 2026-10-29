<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fqmqlk5qm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fqmqlk5qm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:pause-solid" /></template>
