<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e4mj43pwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e4mj43pwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-number-6-filled" /></template>
