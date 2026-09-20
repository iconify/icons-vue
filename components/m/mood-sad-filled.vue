<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/txyoju1sd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="txyoju1sd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:mood-sad-filled" /></template>
