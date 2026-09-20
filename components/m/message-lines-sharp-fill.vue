<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t770zjbze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t770zjbze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:message-lines-sharp-fill" /></template>
