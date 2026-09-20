<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c71na2-8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c71na2-8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp-color:select-circle-area-2" /></template>
