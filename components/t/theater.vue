<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p3q2l4inj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p3q2l4inj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:theater" /></template>
