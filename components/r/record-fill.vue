<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bl8cagq5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bl8cagq5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:record-fill" /></template>
