<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lhcuh2eux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lhcuh2eux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:message-circle-more" /></template>
