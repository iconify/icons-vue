<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dv1b1wt7j.css';
import '../../css/h/hb1iu0uss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dv1b1wt7j"/><path class="hb1iu0uss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:notebook-pen-filled" /></template>
