<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbrp83znd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kbrp83znd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:sort-0-9" /></template>
