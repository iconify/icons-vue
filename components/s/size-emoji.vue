<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lo_veke7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="lo_veke7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:size-emoji" /></template>
