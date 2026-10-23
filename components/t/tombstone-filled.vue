<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qse2q7bsq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qse2q7bsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:tombstone-filled" /></template>
