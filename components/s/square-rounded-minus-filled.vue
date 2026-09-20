<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ij-lldb6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ij-lldb6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-rounded-minus-filled" /></template>
