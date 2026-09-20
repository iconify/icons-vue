<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kw89gnbud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kw89gnbud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:shield" /></template>
