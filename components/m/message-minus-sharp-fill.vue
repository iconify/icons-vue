<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/thll_7t1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="thll_7t1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:message-minus-sharp-fill" /></template>
