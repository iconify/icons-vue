<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-t87l60n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r-t87l60n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:message-circle-off-filled" /></template>
