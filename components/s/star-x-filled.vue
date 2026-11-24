<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/se_pfbimu.css';
import '../../css/n/n4qsi-ucz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="se_pfbimu"/><path class="n4qsi-ucz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:star-x-filled" /></template>
