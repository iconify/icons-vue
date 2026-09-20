<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zobhzcaid.css';
import '../../css/z/zrdlp3d4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zobhzcaid"/><path class="zrdlp3d4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:ticket-duotone" /></template>
