<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zhslh1nsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zhslh1nsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:rotate-2" /></template>
