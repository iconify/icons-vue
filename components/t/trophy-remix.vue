<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k1q9jbute.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k1q9jbute"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:trophy-remix" /></template>
