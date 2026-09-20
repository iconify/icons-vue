<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qa9n4tmlw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qa9n4tmlw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:medium-logo-1" /></template>
