<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/edi2uybuy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="edi2uybuy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:sonne" /></template>
