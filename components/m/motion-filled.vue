<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/snb_yq7qg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="snb_yq7qg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:motion-filled" /></template>
