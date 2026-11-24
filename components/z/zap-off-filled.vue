<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ej_l1ebmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ej_l1ebmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:zap-off-filled" /></template>
