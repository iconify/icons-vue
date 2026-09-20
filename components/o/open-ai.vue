<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bm_om44gp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":25};
const content = `<path class="bm_om44gp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:open-ai" /></template>
