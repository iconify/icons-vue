<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b49rn0bzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b49rn0bzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:medical-cross-fill-round" /></template>
