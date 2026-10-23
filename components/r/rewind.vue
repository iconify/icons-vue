<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/en74i_bwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="en74i_bwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:rewind" /></template>
