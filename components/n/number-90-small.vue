<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uevygjbmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uevygjbmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:number-90-small" /></template>
