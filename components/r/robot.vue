<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/olf7scbij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="olf7scbij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:robot" /></template>
