<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pqeizzbud.css';
import '../../css/u/umfrdlbme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pqeizzbud"/><path class="umfrdlbme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:shield-house-filled" /></template>
