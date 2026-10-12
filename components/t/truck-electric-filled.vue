<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/now_6ismn.css';
import '../../css/q/q7s1dob3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="now_6ismn"/><path class="q7s1dob3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:truck-electric-filled" /></template>
