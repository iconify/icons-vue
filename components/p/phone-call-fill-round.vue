<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t8mempy0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t8mempy0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:phone-call-fill-round" /></template>
