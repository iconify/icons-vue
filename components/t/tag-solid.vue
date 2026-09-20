<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tclp1ib_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tclp1ib_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:tag-solid" /></template>
