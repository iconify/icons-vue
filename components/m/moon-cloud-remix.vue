<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/emq9xhbfq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="emq9xhbfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:moon-cloud-remix" /></template>
