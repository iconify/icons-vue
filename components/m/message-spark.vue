<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nd57_qkrg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nd57_qkrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:message-spark" /></template>
