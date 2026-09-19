<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_aajjbws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="x_aajjbws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:mic-small" /></template>
