<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lofyd66wj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lofyd66wj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-rounded-letter-v-filled" /></template>
