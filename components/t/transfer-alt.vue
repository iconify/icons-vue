<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hopdzbs7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hopdzbs7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:transfer-alt" /></template>
