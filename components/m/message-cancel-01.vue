<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wk3w14b0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wk3w14b0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:message-cancel-01" /></template>
