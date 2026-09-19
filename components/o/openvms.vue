<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/da3mhqb4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":374,"height":512};
const content = `<path class="da3mhqb4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:openvms" /></template>
