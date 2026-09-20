<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q3ey7ab7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="q3ey7ab7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:user-profile-focus-solid" /></template>
