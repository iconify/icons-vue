<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tos43mmlx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tos43mmlx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:trivy" /></template>
