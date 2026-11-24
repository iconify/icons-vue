<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ks7isf27w.css';
import '../../css/t/tdaucbcdb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ks7isf27w"/><path class="tdaucbcdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:server-off-filled" /></template>
