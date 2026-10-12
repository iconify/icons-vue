<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wey8zoa3m.css';
import '../../css/v/vcmk6cc8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wey8zoa3m"/><path class="vcmk6cc8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:messages-circle-filled" /></template>
