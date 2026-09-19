<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/odpzhpb5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":473,"height":512};
const content = `<path class="odpzhpb5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:templeos" /></template>
