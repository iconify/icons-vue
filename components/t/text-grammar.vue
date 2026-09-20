<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzufplyuq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zzufplyuq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:text-grammar" /></template>
