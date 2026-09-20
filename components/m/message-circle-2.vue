<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lnk8b_buc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lnk8b_buc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:message-circle-2" /></template>
