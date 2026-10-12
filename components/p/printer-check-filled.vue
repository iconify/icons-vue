<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yk30w7bqn.css';
import '../../css/e/e_r9uibzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yk30w7bqn"/><path class="e_r9uibzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:printer-check-filled" /></template>
