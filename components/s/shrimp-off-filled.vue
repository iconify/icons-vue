<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-4qcuqsb.css';
import '../../css/p/picyieb1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k-4qcuqsb"/><path class="picyieb1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:shrimp-off-filled" /></template>
