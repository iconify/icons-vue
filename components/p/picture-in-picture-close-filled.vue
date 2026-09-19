<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t59wq0bcq.css';
import '../../css/e/e71w-2bnu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t59wq0bcq"/><path class="e71w-2bnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:picture-in-picture-close-filled" /></template>
