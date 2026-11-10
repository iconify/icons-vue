<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ae0x7dbsh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ae0x7dbsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:sound-wave-off" /></template>
