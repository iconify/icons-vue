<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/na34i4bqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="na34i4bqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:unlock-gloss" /></template>
