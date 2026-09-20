<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l0m43l0sd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l0m43l0sd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:text-initial" /></template>
