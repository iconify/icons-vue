<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gg6uzp21k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gg6uzp21k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:message-plus" /></template>
