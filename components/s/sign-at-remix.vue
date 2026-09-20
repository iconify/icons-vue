<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ykz1nx-0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ykz1nx-0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:sign-at-remix" /></template>
