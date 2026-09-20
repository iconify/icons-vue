<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rr-c3ypre.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rr-c3ypre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-rounded-letter-j-filled" /></template>
