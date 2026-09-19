<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uml44qbtq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uml44qbtq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:queue-01" /></template>
