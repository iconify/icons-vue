<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x72_jn4yw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x72_jn4yw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:rectangle-horizontal-filled" /></template>
