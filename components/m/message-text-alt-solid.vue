<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_3vepb9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="e_3vepb9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:message-text-alt-solid" /></template>
