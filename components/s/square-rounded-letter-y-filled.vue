<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k7r9tlz2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k7r9tlz2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-rounded-letter-y-filled" /></template>
