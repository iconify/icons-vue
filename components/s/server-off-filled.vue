<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tx0z78bot.css';
import '../../css/t/tdaucbcdb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tx0z78bot"/><path class="tdaucbcdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:server-off-filled" /></template>
