<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tvgxz_baw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tvgxz_baw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:template-filled" /></template>
