<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wfyfzv5at.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wfyfzv5at"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:x-sharp-duotone" /></template>
