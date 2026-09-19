<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uul-ip37v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uul-ip37v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:sign-division-slash-duotone" /></template>
