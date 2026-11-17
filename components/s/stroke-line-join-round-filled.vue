<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/srv_qk7md.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="srv_qk7md"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:stroke-line-join-round-filled" /></template>
