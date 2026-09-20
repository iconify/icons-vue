<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhicr5bdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yhicr5bdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:message-off-sharp" /></template>
