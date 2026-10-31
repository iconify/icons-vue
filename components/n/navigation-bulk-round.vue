<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lr47oovvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lr47oovvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:navigation-bulk-round" /></template>
