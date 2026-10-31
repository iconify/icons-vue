<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bprw-4yaq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bprw-4yaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:shuffle-gloss" /></template>
