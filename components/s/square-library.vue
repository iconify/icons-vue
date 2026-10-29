<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ob4h7naqq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ob4h7naqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:square-library" /></template>
