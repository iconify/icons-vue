<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b87657bsl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b87657bsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tablet-bulk-round" /></template>
