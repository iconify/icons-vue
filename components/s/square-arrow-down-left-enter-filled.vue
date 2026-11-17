<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cyk9e30qv.css';
import '../../css/t/ta5emobsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cyk9e30qv"/><path class="ta5emobsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-arrow-down-left-enter-filled" /></template>
