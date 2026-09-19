<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-0xczbbt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="z-0xczbbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:os2" /></template>
