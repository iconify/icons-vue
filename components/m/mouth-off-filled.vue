<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bfza2kq2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bfza2kq2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:mouth-off-filled" /></template>
