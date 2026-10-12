<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aa-f6fb0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aa-f6fb0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:van-filled" /></template>
